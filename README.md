# Tokyo Olympic Azure Aata Engineering Project

## Overview
This project demonstrates the implementation of a Data Engineering Pipeline following the Medallion Architecture. The pipeline ingests raw data through HTTP requests into an Azure Data Lake, performs data transformation using Azure Databricks, and stores the processed data back into the data lake. Further analysis is conducted by running SQL queries in Azure Synapse Analytics and visualizing the insights in Power BI.

## Project Workflow
### 1. Data Ingestion
Utilized HTTP requests to fetch raw data from the source system.
Stored the raw data in the Bronze Layer of the Azure Data Lake.
### 2. Data Transformation
Leveraged Azure Databricks for data cleaning, transformation, and enrichment.
Processed data was moved to the Silver Layer in the data lake, ensuring standardized and structured data.
### 3. Data Storage
Transformed data was further aggregated and stored in the Gold Layer of the Azure Data Lake for analytical use.
### 4. Data Analysis
Integrated the Azure Synapse Analytics workspace to run complex SQL queries on the Gold Layer data.
Built a connection between Azure Synapse and Power BI to create interactive dashboards for data visualization and business intelligence.

## Key Features
Medallion Architecture: Ensures a robust and scalable data pipeline with clearly defined layers (Bronze, Silver, Gold).
Azure Data Lake Storage Gen2: Centralized storage for raw and processed data.
Azure Databricks: Scalable and distributed data transformation.
Azure Synapse Analytics: Enables seamless querying of processed data using SQL.
Power BI Integration: Provides actionable insights through interactive dashboards.

## Technology Stack
Azure Data Lake Storage Gen2: Cloud-based data storage.
Azure Databricks: For data transformation and processing.
Azure Synapse Analytics: For running SQL queries on processed data.
Power BI: For visualization and reporting.
Python: For scripting and automation of the pipeline.
REST API: For data ingestion via HTTP requests.
