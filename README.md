# Blockchain and Stock Market Analysis Using Apache Spark

This project demonstrates a scalable data analytics pipeline using Apache Spark. It focuses on analyzing blockchain transaction metadata and high-frequency stock prices using distributed processing techniques.

## Project Overview

The pipeline was built to explore how big data tools can uncover trends and patterns across financial datasets stored in HDFS. PySpark was used for both transformation and querying stages.

## Datasets

- **Blockchain Data**: Block heights, sizes, transaction counts, and timestamps.
- **Stock Market Data**: Historical pricing data for companies like AAPL, GOOGL, TSLA.

## Technologies Used

- Apache Spark (Core and SQL APIs)
- Hadoop Distributed File System (HDFS)
- Python with PySpark

## Key Features

- Loads raw CSVs from HDFS and parses them into structured RDDs and DataFrames.
- Applies SQL-style queries to extract meaningful insights.
- Identifies:
  - Largest blockchain block and max transaction counts
  - Peak stock prices and their corresponding timestamps
- Optimized to handle large volumes using Spark's parallel processing engine.

## Sample Analyses

- Total number of unique blocks and high-value transactions
- Peak and dip stock prices across multiple companies
- Temporal distribution of transaction activity

## Learning Objectives

- Build an ETL pipeline on distributed architecture
- Use Spark SQL for complex financial queries
- Handle real-world structured and semi-structured data efficiently
