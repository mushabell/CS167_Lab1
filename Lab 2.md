# Lab 2

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

* (Q1) Copy the output of the command `hdfs dfsadmin -report`.\
  The output of the command is:\
Configured Capacity: 207929917440 (193.65 GB)\
Present Capacity: 173144121344 (161.25 GB)\
DFS Remaining: 173144096768 (161.25 GB)\
DFS Used: 24576 (24 KB)\
DFS Used%: 0.00%\
Replicated Blocks:\
        Under replicated blocks: 0\
        Blocks with corrupt replicas: 0\
        Missing blocks: 0\
        Missing blocks (with replication factor 1): 0\
        Low redundancy blocks with highest priority to recover: 0\
        Pending deletion blocks: 0\
Erasure Coded Block Groups: \
        Low redundancy block groups: 0\
        Block groups with corrupt internal blocks: 0\
        Missing block groups: 0\
        Low redundancy blocks with highest priority to recover: 0\
        Pending deletion blocks: 0\                                                                              
Live datanodes (1):                                                                                                             
                                                                                                                                
Name: 169.235.28.134:9866 (class-134.cs.ucr.edu)                                                                                
Hostname: class-134.cs.ucr.edu                                                                                                  
Decommission Status : Normal                                                                                                    
Configured Capacity: 207929917440 (193.65 GB)                                                                                   
DFS Used: 24576 (24 KB)                                                                                                         
Non DFS Used: 34769018880 (32.38 GB)                                                                                            
DFS Remaining: 173144096768 (161.25 GB)                                                                                         
DFS Used%: 0.00%                                                                                                                
DFS Remaining%: 83.27%                                                                                                          
Configured Cache Capacity: 0 (0 B)                                                                                              
Cache Used: 0 (0 B)                                                                                                             
Cache Remaining: 0 (0 B)                                                                                                        
Cache Used%: 100.00%                                                                                                            
Cache Remaining%: 0.00%                                                                                                         
Xceivers: 0                                                                                                                     
Last contact: Fri Aug 08 00:52:15 PDT 2025                                                                                      
Last Block Report: Fri Aug 08 00:51:27 PDT 2025                                                                                 
Num of Blocks: 0 

* (Q2) What is the total capacity of this cluster and how much of it is free? and how many live data nodes are there?\
  Total capacity: 193.65 GB\
  Free capacity: 161.25 GB\
  Live nodes: 1

* (Q3) What is the output of the command `hdfs dfs -ls` after you copied the text file?\
  The output is:\
  Found 1 items                                                                                                                   
-rw-r--r--   3 cs167 supergroup          0 2025-08-08 01:01 abell062.txt  

* (Q4) Does the program run after you change the default file system to HDFS? What is the error message, if any, that you get?\
  No the program does not run. I get the error: 
  Input file 'DFS[DFSClient[clientName=DFSClient_NONMAPREDUCE_-1793876227_1, ugi=cs167 (auth:SIMPLE)]]' does not exist!

* (Q5) Verify the copied file (`copy.csv`) size and report the running time.\
  The file size was 2271210910 bytes and it took 155851.822211 seconds to run the program.

* (Q6) Report the running time of the cp command.\
  The time of the cp command is:\
  real    0m2.150s\
  user    0m0.004s\
  sys     0m2.142s

* (Q7) How do the two numbers in (Q5) and (Q6) compare? (The running times of copying the file through your program and the operating system.) Explain IN YOUR OWN WORDS why you see these results.\
  The cp system processing is faster because it is meant to be used in local file systems and is more optamized to work there. Our program uses hadoop, which is good for systems that are localed in different places which means the level of abstraction of what the code is doing is a lot more compared to the command 'cp'. This makes the 'cp' command faster while our code takes longer due to hadoop. 

* (Q8) Use your program to test the following cases and report the running time for each case.
1) Copy a file from local file system to HDFS.\
   156053.913393 seconds
3) Copy a file from HDFS to local file system.\
   096.683305 seconds
4) Copy a file from HDFS to HDFS.\
   156142.732470 seconds
