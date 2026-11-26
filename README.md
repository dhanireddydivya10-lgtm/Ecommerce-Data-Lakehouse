# Ecommerce-Data-Lakehouse
End-to-End Data Lakehouse Project using Databricks, PySpark and Delta Lake 
This project implements an end-to-end E-Commerce Data Lakehouse using Azure Databricks, PySpark, Delta Lake, and SQL.
The goal is to process raw product data through Bronze, Silver, and Gold layers and prepare it for analytics.
## Technologies Used
- Azure Databricks
- Python
- PySpark
- Delta Lake
- SQL
- Kaggle Dataset

## Dataset
E-Commerce and Retail Datasets 2025.
The dataset contains product information such as product title, brand, prices, discounts, ratings, seller details, and stock availability.

## Project Architecture
### Bronze Layer
- Ingested raw CSV data using Auto Loader.
- Stored raw data as a Delta table.

### Silver Layer
- Cleaned and transformed the data.
- Handled missing and duplicate records.
- Converted numeric columns into appropriate data types.

### Gold Layer
- Created brand-level summary metrics.
- Calculated product counts, average prices, discounts, ratings, and total ratings.

## Delta Lake Features
- MERGE operation
- Time Travel
- Schema Evolution
- OPTIMIZE
- Z-ORDER

## SQL Analytics
- Brand-wise product summary
- Highest discount products
- Stock availability analysis

## Project Outcome
Built a basic end-to-end data lakehouse pipeline demonstrating data ingestion, transformation, storage, optimization, and analytics using Databricks.



