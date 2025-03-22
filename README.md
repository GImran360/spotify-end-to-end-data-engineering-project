# spotify-end-to-end-data-engineering-project
## Introduction 

📊 In this project, we will retrieve data from the Spotify API, transform it into the desired format 🎵, and load it into the AWS data store ☁️. Using AWS services, we aim to drive data-driven business decisions 📈✨.

## high-level architecture
![high-level architecture](https://github.com/GImran360/spotify-end-to-end-data-engineering-project/blob/main/Spotify%20data%20pipe%20line.jpg)

## 🎵 Spotify API Project 🎵

This API provides comprehensive information about music artists, albums, and songs. 🎶✨ 
![Spotify API](https://developer.spotify.com/documentation/web-api)

## 🎯 Services Used

1️⃣ S3 (Simple Storage Service) 🗄️📦
Amazon S3 is a highly scalable object storage service that enables you to store and retrieve unlimited data from anywhere. It's widely used for storing large media files, backups, and static website content. 🌐📂

2️⃣ AWS Lambda ⚡🖥️
AWS Lambda is a serverless computing service that allows you to run code without managing servers. It executes code in response to events, such as changes in S3 or DynamoDB, ensuring efficient, event-driven processing. 🚀📊

3️⃣ Amazon CloudWatch 📊⏰
Amazon CloudWatch is a monitoring service that tracks AWS resources and applications. It helps collect metrics, monitor logs, and set alarms to ensure smooth operations. 📈🔍

4️⃣ AWS Glue Crawler 🔍🤖
AWS Glue Crawler is a fully managed service that scans data sources, identifies formats, and infers schemas to create an AWS Glue Data Catalog. It automates data discovery, making it easier to analyze structured and unstructured data. 📊📜

5️⃣ AWS Glue Data Catalog 📖🛠️
The AWS Glue Data Catalog is a metadata repository that simplifies data management in AWS. It integrates with services like Athena for seamless data discovery and querying. 🗂️🔗

6️⃣ Amazon Athena 🏹🔍
Amazon Athena is an interactive SQL-based query service that enables analysis of data stored in Amazon S3. It processes large datasets efficiently, providing quick insights without requiring complex infrastructure. 📊🚀

### Installed Packges 
```
pip instal pandas
pip install numpy
pip install spotift
``` 
