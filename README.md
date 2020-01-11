## Udacity Data Engineering Nanodegree - Project 3 Data Wareohousing
The purpose of this project is to extract data from Sparkify event logs and song logs and transform it into Fact tables and Dimension Tables in the Redshift Cluster

### ETL Details
- The logs are stored in S3 for both Events and Songs
- The staging tables are used to read the logs and insert it into a tables
- The code then read the staging table and transform it into the fact and dimensions table
- The songplay table is the fact table and it stores all details about the song, user id and levels, artist and duration of the song for fast reading on analytics
- The fact table (songplay) has the details needed to know about the popularity, details of users listening to certain song based on certain time period etc.

## Running the code
- Fill in the config file with your AWS Redshift and IAM details
- Run ***create_tables.py*** to create all the tables
- Run ***etl.py*** to start the ETL Pipeline
- Check that the data has been inserted by Query in Redshift console.

### Written by Andree Wijaya