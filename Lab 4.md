# Lab 4

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

* (Q1) What do you think the line `job.setJarByClass(Filter.class);` does?\
  setJarByClass specifies the specific class that we should use for the jar file. This is applied on the Job titled job. 

* (Q2) What is the effect of the line `job.setNumReduceTasks(0);`?\
This line sets the number of redusers to zero on the job and this means there will no reduce-phase, only a map phase. 

* (Q3) How many lines do you see in the output?\
  There is a lot of lines in the output. I have added the output to the under because it is a lot of lines to count.\
  2025-08-21 11:15:34,837 INFO impl.MetricsConfig: Loaded properties from hadoop-metrics2.properties
2025-08-21 11:15:34,914 INFO impl.MetricsSystemImpl: Scheduled Metric snapshot period at 10 second(s).
2025-08-21 11:15:34,914 INFO impl.MetricsSystemImpl: JobTracker metrics system started
2025-08-21 11:15:35,023 WARN mapreduce.JobResourceUploader: Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.
2025-08-21 11:15:35,106 INFO input.FileInputFormat: Total input files to process : 1
2025-08-21 11:15:35,165 INFO mapreduce.JobSubmitter: number of splits:2
2025-08-21 11:15:35,280 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_local2123782245_0001
2025-08-21 11:15:35,281 INFO mapreduce.JobSubmitter: Executing with tokens: []
2025-08-21 11:15:35,401 INFO mapreduce.Job: The url to track the job: http://localhost:8080/
2025-08-21 11:15:35,402 INFO mapred.LocalJobRunner: OutputCommitter set in config null
2025-08-21 11:15:35,402 INFO mapreduce.Job: Running job: job_local2123782245_0001
2025-08-21 11:15:35,406 INFO output.PathOutputCommitterFactory: No output committer factory defined, defaulting to FileOutputCommitterFactory
2025-08-21 11:15:35,407 INFO output.FileOutputCommitter: File Output Committer Algorithm version is 2
2025-08-21 11:15:35,407 INFO output.FileOutputCommitter: FileOutputCommitter skip cleanup _temporary folders under output directory:false, ignore cleanup failures: false
2025-08-21 11:15:35,408 INFO mapred.LocalJobRunner: OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter
2025-08-21 11:15:35,442 INFO mapred.LocalJobRunner: Waiting for map tasks
2025-08-21 11:15:35,443 INFO mapred.LocalJobRunner: Starting task: attempt_local2123782245_0001_m_000000_0
2025-08-21 11:15:35,459 INFO output.PathOutputCommitterFactory: No output committer factory defined, defaulting to FileOutputCommitterFactory
2025-08-21 11:15:35,460 INFO output.FileOutputCommitter: File Output Committer Algorithm version is 2
2025-08-21 11:15:35,460 INFO output.FileOutputCommitter: FileOutputCommitter skip cleanup _temporary folders under output directory:false, ignore cleanup failures: false
2025-08-21 11:15:35,475 INFO mapred.Task:  Using ResourceCalculatorProcessTree : [ ]
2025-08-21 11:15:35,479 INFO mapred.MapTask: Processing split: hdfs://class-133:9000/user/cs167/nasa_19950801.tsv:0+134217728
2025-08-21 11:15:36,412 INFO mapreduce.Job: Job job_local2123782245_0001 running in uber mode : false
2025-08-21 11:15:36,413 INFO mapreduce.Job:  map 0% reduce 0%
2025-08-21 11:15:36,443 INFO mapred.LocalJobRunner: 
2025-08-21 11:15:36,455 INFO mapred.Task: Task:attempt_local2123782245_0001_m_000000_0 is done. And is in the process of committing
2025-08-21 11:15:36,458 INFO mapred.LocalJobRunner: 
2025-08-21 11:15:36,459 INFO mapred.Task: Task attempt_local2123782245_0001_m_000000_0 is allowed to commit now
2025-08-21 11:15:36,486 INFO output.FileOutputCommitter: Saved output of task 'attempt_local2123782245_0001_m_000000_0' to hdfs://class-133:9000/user/cs167/filter_output_dir
2025-08-21 11:15:36,487 INFO mapred.LocalJobRunner: map
2025-08-21 11:15:36,487 INFO mapred.Task: Task 'attempt_local2123782245_0001_m_000000_0' done.
2025-08-21 11:15:36,491 INFO mapred.Task: Final Counters for attempt_local2123782245_0001_m_000000_0: Counters: 21
        File System Counters
                FILE: Number of bytes read=4777
                FILE: Number of bytes written=640818
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=134221824
                HDFS: Number of bytes written=0
                HDFS: Number of read operations=9
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=3
                HDFS: Number of bytes read erasure-coded=0
        Map-Reduce Framework
                Map input records=1255167
                Map output records=0
                Input split bytes=115
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=25
                Total committed heap usage (bytes)=322961408
        File Input Format Counters
                Bytes Read=134221824
        File Output Format Counters 
                Bytes Written=0
2025-08-21 11:15:36,492 INFO mapred.LocalJobRunner: Finishing task: attempt_local2123782245_0001_m_000000_0
2025-08-21 11:15:36,492 INFO mapred.LocalJobRunner: Starting task: attempt_local2123782245_0001_m_000001_0
2025-08-21 11:15:36,493 INFO output.PathOutputCommitterFactory: No output committer factory defined, defaulting to FileOutputCommitterFactory
2025-08-21 11:15:36,494 INFO output.FileOutputCommitter: File Output Committer Algorithm version is 2
2025-08-21 11:15:36,494 INFO output.FileOutputCommitter: FileOutputCommitter skip cleanup _temporary folders under output directory:false, ignore cleanup failures: false
2025-08-21 11:15:36,494 INFO mapred.Task:  Using ResourceCalculatorProcessTree : [ ]
2025-08-21 11:15:36,496 INFO mapred.MapTask: Processing split: hdfs://class-133:9000/user/cs167/nasa_19950801.tsv:134217728+33596042
2025-08-21 11:15:36,686 INFO mapred.LocalJobRunner: 
2025-08-21 11:15:36,690 INFO mapred.Task: Task:attempt_local2123782245_0001_m_000001_0 is done. And is in the process of committing
2025-08-21 11:15:36,693 INFO mapred.LocalJobRunner: 
2025-08-21 11:15:36,693 INFO mapred.Task: Task attempt_local2123782245_0001_m_000001_0 is allowed to commit now
2025-08-21 11:15:36,702 INFO output.FileOutputCommitter: Saved output of task 'attempt_local2123782245_0001_m_000001_0' to hdfs://class-133:9000/user/cs167/filter_output_dir
2025-08-21 11:15:36,702 INFO mapred.LocalJobRunner: map
2025-08-21 11:15:36,703 INFO mapred.Task: Task 'attempt_local2123782245_0001_m_000001_0' done.
2025-08-21 11:15:36,703 INFO mapred.Task: Final Counters for attempt_local2123782245_0001_m_000001_0: Counters: 21
        File System Counters
                FILE: Number of bytes read=5026
                FILE: Number of bytes written=640818
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=167817866
                HDFS: Number of bytes written=0
                HDFS: Number of read operations=15
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=5
                HDFS: Number of bytes read erasure-coded=0
        Map-Reduce Framework
                Map input records=314731
                Map output records=0
                Input split bytes=115
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=3
                Total committed heap usage (bytes)=390070272
        File Input Format Counters 
                Bytes Read=33596042
        File Output Format Counters 
                Bytes Written=0
2025-08-21 11:15:36,703 INFO mapred.LocalJobRunner: Finishing task: attempt_local2123782245_0001_m_000001_0
2025-08-21 11:15:36,703 INFO mapred.LocalJobRunner: map task executor complete.
2025-08-21 11:15:37,416 INFO mapreduce.Job:  map 100% reduce 0%
2025-08-21 11:15:37,417 INFO mapreduce.Job: Job job_local2123782245_0001 completed successfully
2025-08-21 11:15:37,423 INFO mapreduce.Job: Counters: 21
        File System Counters
                FILE: Number of bytes read=9803
                FILE: Number of bytes written=1281636
                FILE: Number of read operations=0
                FILE: Number of large read operations=0
                FILE: Number of write operations=0
                HDFS: Number of bytes read=302039690
                HDFS: Number of bytes written=0
                HDFS: Number of read operations=24
                HDFS: Number of large read operations=0
                HDFS: Number of write operations=8
                HDFS: Number of bytes read erasure-coded=0
        Map-Reduce Framework
                Map input records=1569898
                Map output records=0
                Input split bytes=230
                Spilled Records=0
                Failed Shuffles=0
                Merged Map outputs=0
                GC time elapsed (ms)=28
                Total committed heap usage (bytes)=713031680
        File Input Format Counters 
                Bytes Read=167817866
        File Output Format Counters 
                Bytes Written=0

* (Q4) How many files are produced in the output?\
There are 3 output files that are produced, including the _SUCCESS file. 
* (Q5) Explain this number based on the input file size and default block size.\
The default block size is 128MB, and since each of the files for the input are smaller than 128MB there are only 2 files that are produced as the output. 
* (Q6) How many files are produced in the output directory and how many lines are there in each file?\
There are three files that are produced including the _SUCCESS file. There should be 2 lines in each file (not _SUCCESS file) totaling 4 lines. 
* (Q7) Explain these numbers based on the number of reducers and number of response codes in the input file.\
There are 2 reducers which each create their own file making the 2 files  and a success marker file. The number of response codes is 4 because we set the value for the reduce input groups to 4. 
* (Q8) How many files are produced in the output directory and how many lines are there in each file?\
There are 3 output files that are created. There are 7 lines wirrten in total with one file having 3 lines and the other having 4 lines.
* (Q9) Explain these numbers based on the number of reducers and number of response codes in the input file.\
There are 2 reducers which each create their own file making the 2 files a d a success marker file. The number of response codes is 7 because we set the value for the reduce input groups to 7. 
* (Q10) How many files are produced in the output directory and how many lines are there in each file?

* (Q11) Explain these numbers based on the number of reducers and number of response codes in the input file.
