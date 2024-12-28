## Tokyo Olympic Data Analysis - End-to-End Pipeline

## Project Overview
This project demonstrates an end-to-end data engineering pipeline using various Azure services to analyze data from the Tokyo 2020 Olympics. The pipeline extracts data from a GitHub raw URL, ingests and processes it through Azure Data Factory, Azure Data Lake, Azure Databricks, and Azure Synapse Analytics, and finally visualizes the results using Power BI.

The analysis covers various aspects of the Olympic Games, such as athlete performance, medal distribution, and country-wise overall medals.

## Technologies Used
GitHub: Source for raw Olympic data in CSV format.
Azure Data Factory: Used for data ingestion and ETL processes to move data from GitHub to Azure Data Lake.
Azure Data Lake: For data storage in a scalable and secure way.
Azure Databricks: For data transformation using Apache Spark and PySpark.
Azure Synapse Analytics: For big data processing, SQL-based querying, and aggregations.
Power BI: For visualization and reporting of the analyzed data.

## Dataset
The dataset used in this analysis contains the following data:
Athlete Information: Name, country, sport, event, gender, age, etc.
Medal Information: Number of gold, silver, and bronze medals by athlete and country.


## Dataset Source
The data is sourced from raw CSV files hosted on a GitHub repository and processed through the pipeline. It includes the following:
Athlete Data: Information about each athlete, including their nationality, events, and performance.
Medal Data: A record of the medals won by athletes, categorized by gold, silver, and bronze.

## Project Objectives
The main objectives of this project are to:
Extract data from a GitHub raw URL using Azure Data Factory.
Load and store data in Azure Data Lake for scalable and secure storage.
Transform and analyze the data using Azure Databricks with PySpark.
Store aggregated data in Azure Synapse Analytics for big data processing and SQL-based querying.
Visualize insights using Power BI, presenting trends like medal counts, athlete demographics, and top-performing countries.

## Key Features
Data Extraction: Ingest raw CSV files from a GitHub repository URL into Azure Data Lake using Azure Data Factory.
Data Transformation: Use Azure Databricks to clean, aggregate, and transform the data.
Data Aggregation: Calculate total medals by country, and generate other insights using Azure Synapse Analytics.
Visualization: Create interactive reports and dashboards using Power BI.
