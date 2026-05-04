# Cafe Sales Analysis: From Excel to PostgreSQL ☕📊
## Project Overview
This project demonstrates a full data pipeline, starting from raw data management in MS Excel and evolving into a structured relational database using PostgreSQL. The goal was to analyze 500+ cafe transactions to identify revenue drivers and customer preferences.

## Technical Milestones
Data Preparation (Excel): Cleaned and organized 500+ rows of sales data, identifying initial trends via interactive dashboards.
Database Schema Design: Engineered a structured SQL table using precise data types like NUMERIC(10,2) for financial accuracy and DATE for time-series analysis.
Data Migration: Successfully migrated the dataset into PostgreSQL using pgAdmin 4, ensuring 100% data integrity across 501 records.
Business Intelligence: Leveraged SQL queries to perform aggregate analysis (e.g., identifying Chocolate Cake as the top revenue generator).

## Tools Used
Database: PostgreSQL
Management: pgAdmin 4
Spreadsheet: MS Excel
Documentation: GitHub

## Key Insights
Top Seller: Chocolate Cake (Identified via SQL aggregation).
Scale: Managed and queried over 500 transaction records.
Integrity: Zero data loss during the migration from flat files to a relational schema.

## How to Run the Analysis
Create the table using the script in /Scripts/create_table.sql.
Import the Cafe_Sales_Dataset.csv using the pgAdmin Import tool.
Run analysis_queries.sql to view business insights.
