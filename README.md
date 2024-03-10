# Data Engineering YouTube Analysis Project
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.


## Overview

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Project Goals
1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier

## Services we will be using
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.



## Architecture Diagram
![Architecture Diagram](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Project/architecture.jpeg)



## Screenshots

### All Crawlers
![All Crawlers](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/All_Crawlers.png)

### All Jobs in Glue
![All Jobs in Glue](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/All_Jobs_in_Glue.png)

### Cleaned Buckets Data Sources JoinTransform Analysis Bucket
![Cleaned Buckets Data Sources JoinTransform Analysis Bucket](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Cleaned_Buckets_Data_Sources_JoinTransform_Analysis_Bucket.png)

### Dashboard Snippet 1
![Dashboard Snippet 1](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Dashboard_Snippet_1.png)

### Dislikes Heat Map
![Dislikes Heat Map](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Dislikes_Heat_Map.png)

### Donut Chart Dislikes
![Donut Chart Dislikes](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Donut_Chart_Dislikes.png)

### Horizontal Bar Graph
![Horizontal Bar Graph](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Horizontal_Bar_Graph.png)

### Job Runs Activity
![Job Runs Activity](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Job_Runs_Activity.png)

### Lambda function Layers Triggers
![Lambda function Layers Triggers](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Lambda_function_Layers_Triggers.png)

### Lambda function pyspark code
![Lambda function pyspark code](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Lambda_function_pyspark_code.png)

### Likes Views Horizontal Bar Graph
![Likes Views Horizontal Bar Graph](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Likes_Views_Horizontal_Bar_Graph.png)

### Vertical Bar Graph
![Vertical Bar Graph](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Vertical_Bar_Graph.png)

### S3 All Buckets
![S3 All Buckets](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/S3_All_Buckets.png)

## Additional Resources

- [Query editor Athena us-east-2](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Query%20editor%20Athena%20us-east-2.pdf)
- [Roles IAM Global](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Roles%20IAM%20Global.pdf)
- [Script - Editor - AWS Glue Studio](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Script%20-%20Editor%20-%20AWS%20Glue%20Studio.pdf)
- [Visual - Editor - AWS Glue Studio-rawandcleaned-dbandtable-innerjoin-to-target-analyticsbukcetDB&analyticsTable](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/Visual%20-%20Editor%20-%20AWS%20Glue%20Studio-rawandcleaned-dbandtable-innerjoin-to-target-analyticsbukcetDB&analyticsTable.pdf)
- [de-on-youtube-cleansed-useast2-mayurdev - S3 bucket-cleanednewmultiplejson](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/de-on-youtube-cleansed-useast2-mayurdev%20-%20S3%20bucket-cleanednewmultiplejson.pdf)
- [de-on-youtube-raw-useast2-lambda-json-parquet - Lambda-s3](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/de-on-youtube-raw-useast2-lambda-json-parquet%20-%20Lambda-s3.pdf)
- [de-on-youtube-raw-useast2-lambda-json-parquet - Lambda](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/de-on-youtube-raw-useast2-lambda-json-parquet%20-%20Lambda.pdf)
- [final_analytics analysis_dashboard_print](https://github.com/mahanta-mayur/Youtube-Analysis-AWS/blob/main/Screenshots/final_analytics%20analysis_dashboard_print.pdf)





