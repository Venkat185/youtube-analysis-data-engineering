# youtube-analysis-data-engineering
# Data Engineering YouTube Analysis Project 
## Introduction
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.
## Architecture
![Project Architecture](architecture.jpeg)
## Technology Used
1. Programming Language - Python
2. AWS Cloud Platform
## Project Goals
This project aims to establish a robust data engineering pipeline on AWS to analyze YouTube data effectively. Key objectives include:

1. Data Ingestion: Develop a reliable system to extract YouTube data from diverse sources and store it in a centralized data lake on S3.
   
2. ETL Process: Implement an efficient ETL (Extract, Transform, Load) process using AWS Glue to clean, transform, and structure the raw data into a suitable format for analysis.
   
3. Scalable Data Architecture: Design a scalable data architecture that can accommodate increasing data volumes and processing demands.
   
4. Interactive Data Analysis: Utilize AWS Athena to query the data lake and gain valuable 
   insights, enabling data-driven decision-making.

5. Visual Data Exploration: Create interactive dashboards using Amazon QuickSight to visualize 
   key metrics, trends, and patterns in the YouTube data.
## Key AWS Services for the Project
* Amazon S3: A highly scalable object storage service that will store our raw and processed YouTube data.
* AWS IAM: A security service that will control access to our AWS resources, ensuring data privacy and security.
  
* Amazon QuickSight: A powerful business intelligence tool that will visualize our data insights through interactive dashboards.
  
* AWS Glue: A serverless ETL service that will extract, transform, and load our data from various sources into S3.
  
* AWS Lambda: A serverless computing service that will execute data processing tasks and trigger other AWS services.
  
* AWS Athena: A serverless query service that will analyze our data directly in S3, without the need for data warehousing.
   
