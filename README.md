# Stock-_Market_Data_Analysis_Using_Kafka

**Introduction**

This project demonstrates an End-to-End Real-Time Data Pipeline for Stock Market Data using Apache Kafka as the streaming platform. The goal is to build a scalable data engineering workflow that ingests, processes, and analyzes stock data in real-time.


## ⚙️ Technology Stack

| Category         | Tools Used                        |
|------------------|-----------------------------------|
| Programming      | Python (Pandas, Boto3)            |
| Cloud Platform   | AWS (EC2, S3, Glue, Athena)       |
| Streaming Platform| Apache Kafka                     |
| Orchestration    | Manual commands (can extend to Airflow if needed) |
| Query Language   | SQL (Athena Queries)              |


## 🚀 Project Flow
1. Producer Simulation (Python) - Reads data from CSV and pushes records to a Kafka Topic.
2. Kafka (Running on EC2) - Handles the streaming data pipeline.
3. Consumer (Python) - Consumes the data from Kafka and writes to S3.
4. Glue Crawler - Automatically catalogs the data stored in S3.
5. Athena - Queries the real-time data for analytics.

## Key Learnings

• Real-time data streaming with Kafka.

•  Processing data with Python (Pandas, Boto3).

•  Storing and cataloging data in AWS S3 using Glue.

•  Querying and analyzing data with Athena.

•  Building end-to-end data engineering pipelines.


