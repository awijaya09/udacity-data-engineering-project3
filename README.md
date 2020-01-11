## Udacity Data Engineering Nanodegree - Project 3 Data Wareohousing
The purpose of this project is to extract data from Sparkify event logs and song logs and transform it into Fact tables and Dimension Tables in the Redshift Cluster

### ETL Details
- The logs are stored in S3 for both Events and Songs
- The staging tables are used to read the logs and insert it into a tables
- The code then read the staging table and transform it into the fact and dimensions table
- The songplay table is the fact table and it stores all details about the song, user id and levels, artist and duration of the song for fast reading on analytics

### Written by Andree Wijaya