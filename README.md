
This file details and describes all the attached files for the Spark

Tools Used:
1.	Python3 – Microsoft VScode
2.	Apache Spark (On GCP Cluster)
3.	GCP services – DataProc/GCS 
4.	Jupyter Lab
5.	Apache Hive

Files Attached:
1.	Spark_Ass2.pdf – This file
2.	Spark_MovieRating.– Pyspark File that details all the analysis


Process and File Descriptions:

Step 1:

I placed the three csv files in the HDFS location and ingested them into their respective spark dataframes. The three frames being
•	Movies
•	Ratings
•	Tags


![PY_SPARK_1](https://github.com/user-attachments/assets/97e3b6c8-dc49-47de-9a72-e1d8eacb6f7f)



Step 2:

I then used spark SQL to query the dataframes to get the required outputs. This involved creating tempviews of movies,ratings and tags


![spark_2](https://github.com/user-attachments/assets/f93d5ef3-b63d-47ee-8442-10a38e305933)




Step 3:

I made sure to save the output in a HDFS location. I also checked the files in the HDFS Namenode using the UI.

![spark_3](https://github.com/user-attachments/assets/083cd9bf-4d36-4785-a8f9-a141051aaf07)



