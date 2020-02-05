# Data_Analysis_Hadoop_Stack
Data analysis on StackExchange answers using various tools of the Hadoop stack- PIG, HIVE and MapReduce

TF-IDF stands for term frequency-inverse document frequency. It is a statistical measure which examines the relevance of a word to a document, in a collection of documents. It is calculated by multiplying how many times a word appears in a document with the inverse document frequency across the set of documents.
Steps involved:
1.	Acquiring top 200,00 records from Stackexchange based on View Count
2.	Uploading the records file to Hadoop cluster and Performing ETL operations using PIG
3.	Querying the cleaned records using HIVE
4.	Calculating TF-IDF with 3 phases of MapReduce, while removing the “stop words”, to find the top 10 terms for each of the top 10 users

Refer to the ‘Screenshots.word’ file for detailed steps.

References:
1.	TF-IDF
https://monkeylearn.com/blog/what-is-tf-idf/
2.	Hadoop stack programming
https://www.coursera.org/lecture/hadoop/overview-of-the-hadoop-stack-ertEr
