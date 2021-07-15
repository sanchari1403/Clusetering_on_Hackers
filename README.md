# Clustering_on_Hackers

A company has been potentially hacked and we aim to find out the types of hackers that have caused the threat.
We have the valuable data about the hacks, including information like session time, locations, wpm typing speed, etc.
The forensic department has also provided us with the meta-data of each session that the hackers used to connect to their servers. We have worked here with such attributes to find out the potential group of hackers.

The company has reseached on the hack and let us know that there are three types of hackers causing the threat. One trend that they have noticed from the market is that these hackers trade-off hacks which means that they should have roughly caused equal number of threats. 

Our aim is to find out the potential groups of hackers and conclude if all these hackers are causing the threat. 

We have used Pyspark, which is a Python API introduced by Apache Spark to perform the clustering using K-Means algorithm on our dataset. Also, here we have used the Databricks notebook to perform the necessary operations because of which the file has been read from the Databricks File System (DBFS).
