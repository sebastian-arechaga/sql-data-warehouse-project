# Data Warehouse and Analytics Project

📖 Project Overview

In this project, I built a modern data warehouse using SQL Server following a medallion architecture (Bronze, Silver, Gold).

Raw data from multiple source systems (ERP and CRM) was ingested, cleaned, and transformed into a structured format optimized for analytics. The final output enables efficient querying and supports business insights through a star schema design.

🎯 Objectives

Design a scalable data warehouse for analytical reporting
Clean and integrate data from multiple sources
Build fact and dimension tables for efficient querying
Generate insights on sales trends, customers, and products
🛠️ Tools & Technologies
SQL Server Express
SQL Server Management Studio (SSMS)
T-SQL (SQL)
Draw.io (for data modeling and architecture diagrams)

🏗️ Data Architecture

This project uses a medallion architecture to organize data into three layers:

Bronze Layer
Raw data ingested directly from CSV files with minimal processing
Silver Layer
Cleaned and standardized data (handling null values, formatting, and inconsistencies)
Gold Layer
Business-ready data structured into a star schema for reporting and analysis

This layered approach improves data quality, maintainability, and query performance.

🧩 Data Modeling

The final data model follows a star schema design:

Fact Table
sales
Dimension Tables
customers
products
dates

This structure simplifies analytical queries and enables efficient aggregation of key metrics.

⚙️ ETL Process

The ETL pipeline was implemented using SQL:

Extract
Imported raw data from ERP and CRM CSV files
Transform
Cleaned missing and inconsistent data
Standardized formats (dates, IDs, text fields)
Combined datasets into a unified structure
Load
Loaded processed data into Silver and Gold layers
Created fact and dimension tables for analysis

📊 Analytics & Insights

The data warehouse supports analytical queries such as:

Identifying top-performing products by revenue
Analyzing customer purchasing behavior
Tracking sales trends over time
