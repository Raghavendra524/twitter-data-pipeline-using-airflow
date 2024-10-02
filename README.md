# twitter-airflow-data-engineering-project

## Introduction

The goal of this project is to perform data analytics on twitter data using various tools and technologies, including s3 Storage, Python, EC2 Instance, Airflow Tool.

## Architecture 
![Screenshot (340)](https://github.com/user-attachments/assets/66f6adba-ea20-4c0b-b121-6e996f3afb0a)

## Technology Used
- Programming Language - Python
- Workflow Management Tool - Airflow
Amazon Web Services
1. EC2 Instance
2. S3 storage 

## Step by Step Process
1. Open account in twitter API website, retrieve the twitter raw data using access key and consumer keys
2. Launch EC2 instance in AWS platform
3. Install and deploy Airflow, pandas, tweepy as mentioned in twitter_commands.sh file into instance.
4. put the twitter_dag.py and twitter_etl.py files in airflow project
5. Check the workflow of the project in Airflow.
6. output the csv file into S3 storage.
