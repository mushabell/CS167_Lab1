# Lab 3

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

1. ***(Q1) Compare `bytesRead` and `length`, are they equal? Use one sentance to explain why.***



2. ***(Q2) Copy the output of this command.***\
Configured Capacity: 831719669760 (774.60 GB)
Present Capacity: 576088977408 (536.52 GB)
DFS Remaining: 576088850432 (536.52 GB)
DFS Used: 126976 (124 KB)
DFS Used%: 0.00%
Replicated Blocks:
        Under replicated blocks: 0
        Blocks with corrupt replicas: 0
        Missing blocks: 0
        Missing blocks (with replication factor 1): 0
        Low redundancy blocks with highest priority to recover: 0
        Pending deletion blocks: 0
Erasure Coded Block Groups: 
        Low redundancy block groups: 0
        Block groups with corrupt internal blocks: 0
        Missing block groups: 0
        Low redundancy blocks with highest priority to recover: 0
        Pending deletion blocks: 0
-------------------------------------------------
Live datanodes (4):

Name: 169.235.28.134:9866 (class-134.cs.ucr.edu)
Hostname: class-134.cs.ucr.edu
Decommission Status : Normal
Configured Capacity: 207929917440 (193.65 GB)
DFS Used: 28672 (28 KB)
Non DFS Used: 46750257152 (43.54 GB)
DFS Remaining: 161162854400 (150.09 GB)
DFS Used%: 0.00%
DFS Remaining%: 77.51%
Configured Cache Capacity: 0 (0 B)
Cache Used: 0 (0 B)
Cache Remaining: 0 (0 B)
Cache Used%: 100.00%
Cache Remaining%: 0.00%
Xceivers: 0
Last contact: Mon Aug 18 17:00:50 PDT 2025
Last Block Report: Mon Aug 18 16:18:02 PDT 2025
Num of Blocks: 0


Name: 169.235.28.135:9866 (class-135.cs.ucr.edu)
Hostname: class-135.cs.ucr.edu
Decommission Status : Normal
Configured Capacity: 207929917440 (193.65 GB)
DFS Used: 32768 (32 KB)
Non DFS Used: 112053579776 (104.36 GB)
DFS Remaining: 95859527680 (89.28 GB)
DFS Used%: 0.00%
DFS Remaining%: 46.10%
Configured Cache Capacity: 0 (0 B)
Cache Used: 0 (0 B)
Cache Remaining: 0 (0 B)
Cache Used%: 100.00%
Cache Remaining%: 0.00%
Xceivers: 0
Last contact: Mon Aug 18 17:00:48 PDT 2025
Last Block Report: Mon Aug 18 16:04:12 PDT 2025
Num of Blocks: 0


Name: 169.235.28.137:9866 (class-137.cs.ucr.edu)
Hostname: class-137.cs.ucr.edu
Decommission Status : Normal
Configured Capacity: 207929917440 (193.65 GB)
DFS Used: 32768 (32 KB)
Non DFS Used: 54782779392 (51.02 GB)
DFS Remaining: 153130328064 (142.61 GB)
DFS Used%: 0.00%
DFS Remaining%: 73.65%
Configured Cache Capacity: 0 (0 B)
Cache Used: 0 (0 B)
Cache Remaining: 0 (0 B)
Cache Used%: 100.00%
Cache Remaining%: 0.00%
Xceivers: 0
Last contact: Mon Aug 18 17:00:50 PDT 2025
Last Block Report: Mon Aug 18 16:15:56 PDT 2025
Num of Blocks: 0


Name: 169.235.28.138:9866 (class-138.cs.ucr.edu)
Hostname: class-138.cs.ucr.edu
Decommission Status : Normal
Configured Capacity: 207929917440 (193.65 GB)
DFS Used: 32768 (32 KB)
Non DFS Used: 41976967168 (39.09 GB)
DFS Remaining: 165936140288 (154.54 GB)
DFS Used%: 0.00%
DFS Remaining%: 79.80%
Configured Cache Capacity: 0 (0 B)
Cache Used: 0 (0 B)
Cache Remaining: 0 (0 B)
Cache Used%: 100.00%
Cache Remaining%: 0.00%
Xceivers: 0
Last contact: Mon Aug 18 17:00:50 PDT 2025
Last Block Report: Mon Aug 18 16:05:50 PDT 2025
Num of Blocks: 0



3. ***(Q3) How many live datanodes are in this cluster?***\
There are 5 live datanodes in this cluster.


4. ***(Q4) How many replicas are stored on the namenode? How many replicas are stored in the datanodes?***\
There are 0 replicas stored on the namenode. There are 0 replicas stroed in the datanodes. 


5. ***(Q5) How many replicas are stored on the datanode uploading the file? How many replicas are stored across other datanodes?***




6. ***(Q6) Compare your results of Q4 and Q5, give one sentence to explain the results you obtained.***



7. ***(Q7) Include the output of the three cases above in your README file.***


  | offset | length | bytesRead  | numMatchingLines |
  | ------ | ------ | ---------- | ---------------- |
  | 500    | 1000   |            |                  |
  | 12000  | 1000   |            |                  |
  | 100095 | 1000   |            |                  |
