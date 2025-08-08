# Lab 1

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

- ***(Q1) What is the name of the directory that `mvn archectype:generate` command creates?***\
  The name of the directory is abell062_lab1, or the person's netID followed by "_lab1"


- ***(Q2) What do you see at the console output when you run the `java` command?***\
  The console output when I run the 'java' command is: Hello world!


- ***(Q3) Which of the following is the right way to call the `IsEven` function?***

    - IsEven(5)
    - IsEven.apply(5)
    - new IsEven().apply(5)\
      IsEven(5) is not the correct way to call the function because to use the function we need to use the apply(5). \
      IsEven.apply(5) is not the correct way to call the function because to use the function we need to create an object using the key word new. \
      new IsEven().apply(5) is the right way to call the function because this creates a new object and calls the function through apply. 

- ***(Q4) Did the program compile after you added the `base=0` line?***\
  No, the code did not complie after adding the 'base=0' line.


- ***(Q5) If your answer to (Q4) is No, what is the error message you get?***\
  The error message that I recieved is "Local variable base is required to be final or effectively final based on its usage".






# Lab 2

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

* (Q1) Copy the output of the command `hdfs dfsadmin -report`.

* (Q2) What is the total capacity of this cluster and how much of it is free? and how many live data nodes are there?

* (Q3) What is the output of the command `hdfs dfs -ls` after you copied the text file?

* (Q4) Does the program run after you change the default file system to HDFS? What is the error message, if any, that you get?

* (Q5) Verify the copied file (`copy.csv`) size and report the running time.

* (Q6) Report the running time of the cp command.

* (Q7) How do the two numbers in (Q5) and (Q6) compare? (The running times of copying the file through your program and the operating system.) Explain IN YOUR OWN WORDS why you see these results.

* (Q8) Use your program to test the following cases and report the running time for each case.
1) Copy a file from local file system to HDFS.
2) Copy a file from HDFS to local file system.
3) Copy a file from HDFS to HDFS.
