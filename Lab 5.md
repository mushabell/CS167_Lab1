# Lab 5

## Student information

* Full name: Amshu Bellur
* E-mail: abell062@ucr.edu
* UCR NetID: abell062
* Student ID: 862412968

## Answers

* (Q1) Do you think it will use your local cluster? Why or why not?\
I think it will use the local cluster because when looking at the output, the executor runs on class 134 which is my local class.
* (Q2) Does the application use the cluster that you started? How did you find out?\
Yes, the application uses the cluster that I started and I know this because it connected to the spark master when the output had "Connecting to master spark://class-133:7077..." and used worker nodes when the output had "Executor added: app-20250828195352-0000/0 on worker-20250828194306-169.235.28.134-39665
Executor added: app-20250828195352-0000/1 on worker-20250828103746-169.235.28.137-37201".
* (Q3) What is the Spark master printed on the standard output on IntelliJ IDEA?\
The spark master did not print anything in the standard output. 
* (Q4) What is the Spark master printed on the standard output on the terminal?\
The spark master printed: Using Spark master 'spark://class-133:7077'
* (Q5) For the previous command that prints the number of matching lines, how many tasks were created, and how much time it took to process each task.\
  There was a total of 4 tasks that were created. There were 2 in stage 0 and 2 in stage 1. In stage 0, the tasks took 1477 ms and 1393 ms. In stage 1, the tasks took 116 ms and 1122 ms.
* (Q6) For the previous command that counts the lines and prints the output, how many tasks in total were generated?

* (Q7) Compare this number to the one you got earlier.

* (Q8) Explain why we get these numbers.

* (Q9) What can you do to the current code to ensure that the file is read only once?

* (Q10) How many stages does your program have, and what are the steps in each stage? 

* (Q11) Why does your program have two stages?
