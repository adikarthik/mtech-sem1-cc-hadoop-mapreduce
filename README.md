#2020MT13262 - Adikarthik Gupta C B
---
---
 Map Reduce
---
MapReduce is a processing technique and a program model for distributed computing based on java. The MapReduce algorithm contains two important tasks, namely Map and Reduce. Map takes a set of data and converts it into another set of data, where individual elements are broken down into tuples (key/value pairs).

 Commands to build code
---
To build the Jar file use the following commands
````
mvn clean package -DskipTests
````
 command to execute the jar
---
Follow the below steps
````
1. ssh adi@adt-test-ssh.azurehdinsight.net

2. syntax 
yarn jar Adikarthik-Map-Reduce.jar cc.assignment.WordCount

Welcome to CC Assignment
ADIKARTHIK - 2020MT13262
--------------------------------******************--------------------------------
Usage: wordcount <in> <out>

3. Example 
yarn jar Adikarthik-Map-Reduce.jar cc.assignment.WordCount /example/data/adi/cc-assignment.txt /example/data/adi/aditestResult

4. Output
hdfs dfs -cat /example/data/adi/adiTestResult/*
````
 Related Files
---
jar File - ./Adikarthik-Map-Reduce.jar
input File - ./cc-assignment.txt
output File - ./output.txt
result File - ./result.txt