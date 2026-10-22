# Build an AWS ETL Data Pipeline in Python on YouTube Data

Build an AWS ETL Data Pipeline in Python on YouTube Data — AWS Data Engineering project.

## Overview
Many problems exist when deploying or transferring analytics to the cloud. Differences in features between on-premises and cloud data platforms, security, and governance are all technical concerns. The danger of moving on-premises data into the cloud has prompted organizations to limit cloud analytics initiatives, especially in regulated industries where data protection is crucial. Cloud-based safe Data Lake solutions aid in the development of rich analytics on data while classifying it into several storage phases, such as raw, cleansed, and analytical. This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

## Data
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

_Data is not included in this repository._

## Tech stack
➔ Languages SQL, Python3 ➔ Services AWS S3, AWS Glue, QuickSight, AWS Lambda, AWS Athena, AWS IAM

Amazon S3 Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance. Users may save and retrieve any quantity of data using Amazon S3 at any time and from any location.

## How to run

## Project structure
```
.gitignore
Project_Code/
  Code/
    video17 lambda function.py
    video22 Spark code Glue job.py
    video24 Spark code Glue job with pushdown predicate.py
    video8 Amazon S3 CLI copy commands.sh
  Terraform/
    Instructions.md
README.md
```

## Credits
Based on a ProjectPro guided project.
