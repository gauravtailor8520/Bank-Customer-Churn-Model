# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
In this project, you will execute an End-To-End Data Engineering Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL.

## Architecture 
<img src="Architecture.jpg">

# 📈 Stock Market Kafka Real-Time Data Engineering Project

## 📝 Introduction
In this project, we will execute an end-to-end data engineering workflow on real-time stock market data using Kafka. The goal is to build a data pipeline capable of handling streaming data efficiently.

## 🏗️ Architecture
![Architecture](Architecture.jpg)

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Amazon Web Services (AWS)**
  - S3 (Simple Storage Service)
  - Athena
  - Glue Crawler
  - Glue Catalog
  - EC2
- **Apache Kafka**

## 📊 Dataset Used
Any stock market dataset can be used for this project, as the focus is on building the data pipeline rather than analyzing specific data. 

## 🚀 Project Features
- **Real-time data ingestion with Apache Kafka**
- **Storage and processing using AWS services**
- **ETL pipeline setup with Glue and Athena**
- **Scalable and efficient architecture for handling high-volume data**

## 📌 Prerequisites
- Basic knowledge of Python and SQL
- Understanding of AWS services (S3, Athena, Glue, EC2)
- Familiarity with Apache Kafka

## 📂 Project Structure
```plaintext
📦 Stock Market Kafka Real-Time Data Engineering
├── 📜 README.md
├── 📂 Data Pipeline Scripts
│   ├── producer.py  # Kafka Producer for Streaming Data
│   ├── consumer.py  # Kafka Consumer for Processing Data
│   ├── etl.py       # ETL Process using AWS Glue
│   ├── query.sql    # SQL Queries for Athena
├── 📂 Resources
│   ├── Architecture.jpg  # Project Architecture Diagram
│   ├── Configurations.txt  # Configuration Details
└── 📂 Logs
    ├── kafka_logs.log
    ├── processing_logs.log
