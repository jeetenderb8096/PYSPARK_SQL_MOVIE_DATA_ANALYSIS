

Py - Spark / SQL -  (Movie Data Analysis) Documentation 

This file details and describes all the attached files for the Spark Assignment-2

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

 ![PY_SPARK_1](https://github.com/user-attachments/assets/9a7121f0-f21a-43dd-bc97-a5a7eef3dcf2)





Py - Spark / SQL -  (Movie Data Analysis) Documentation 

This file details and describes all the attached files for the Spark Assignment-2

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

 






Step 2:

I then used spark SQL to query the dataframes to get the required outputs. This involved creating tempviews of movies,ratings and tags


 

Step 3:

I made sure to save the output in a HDFS location. I also checked the files in the HDFS Namenode using the UI.

 



Step 2:

I then used spark SQL to query the dataframes to get the required outputs. This involved creating tempviews of movies,ratings and tags


 

Step 3:

I made sure to save the output in a HDFS location. I also checked the files in the HDFS Namenode using the UI.

 


