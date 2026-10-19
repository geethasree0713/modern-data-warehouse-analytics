# Modern Data Warehouse and Analytics Project

## 📌 Overview

This project focuses on building a modern data warehouse using **Microsoft SQL Server and T-SQL** to consolidate sales data from CRM and ERP source systems.

The goal is to transform raw CSV files into clean, structured, and analysis-ready data that can help businesses understand customer behavior, product performance, and sales trends.

This project is based on the learning materials provided by [Data With Baraa](https://github.com/DataWithBaraa/sql-data-warehouse-project), with the aim of understanding data warehousing concepts, SQL-based ETL pipelines, dimensional modeling, and analytics.

## 🏗️ Data Architecture

The project follows the **Medallion Architecture**, which organizes data into three layers:

- **Bronze Layer:** Stores raw data loaded from the source CSV files.
- **Silver Layer:** Cleans, standardizes, and validates data to improve data quality.
- **Gold Layer:** Organizes processed data into business-ready fact and dimension tables for analytics.

## 🎯 Project Objectives

- Integrate data from CRM and ERP systems into a centralized data warehouse.
- Build SQL-based ETL pipelines to load and transform data.
- Identify and resolve data quality issues.
- Design a star schema using fact and dimension tables.
- Perform SQL-based analysis of customer behavior, product performance, and sales trends.
- Document the data architecture and data models for easier understanding and maintenance.

## 🗂️ Repository Structure

```text
sql-data-warehouse-project/
├── 00_setup/              # Setup instructions
├── 01_datasets/           # CRM and ERP source CSV files
│   ├── source_crm/
│   └── source_erp/
├── 02_docs/               # Requirements and documentation
├── 03_scripts/            # SQL scripts
│   ├── init_database.sql
│   ├── bronze/
│   ├── silver/
│   └── gold/
└── 04_tests/              # Data quality tests
```

## 🔄 Data Pipeline

### 1. Data Ingestion — Bronze Layer
- Load raw CRM and ERP data from CSV files into SQL Server.
- Preserve source data for traceability and further processing.

### 2. Data Cleaning — Silver Layer
- Handle missing and inconsistent values.
- Standardize data formats and text fields.
- Validate records and check for duplicates where appropriate.
- Prepare reliable data for analytical modeling.

### 3. Data Modeling — Gold Layer
- Create fact and dimension tables.
- Organize data using a star schema.
- Prepare a structured data model for business reporting and analytics.

### 4. Data Quality and Analytics
- Validate data using SQL queries and quality checks.
- Analyze customer, product, and sales data.
- Derive insights that support business decision-making.

## 🛠️ Technologies Used

- **Database:** Microsoft SQL Server
- **Query Language:** T-SQL
- **Data Sources:** CSV files
- **Data Engineering:** ETL pipelines, data cleansing, data integration
- **Data Modeling:** Medallion Architecture, Star Schema, Fact and Dimension Tables
- **Tools:** SQL Server Management Studio (SSMS), Git, GitHub

## 📊 Business Questions

The warehouse is designed to support questions such as:

- Which products generate the highest sales?
- Which customers contribute the most revenue?
- How do sales vary across product categories?
- What patterns can be identified in customer purchasing behavior?
- Are there missing, inconsistent, or duplicate records in the source data?

## 🚀 Learning Outcomes

Through this project, I aim to strengthen my understanding of:

- SQL Server and advanced SQL queries.
- ETL pipeline development.
- Data cleaning and validation.
- Data warehouse architecture.
- Fact and dimension table design.
- Star schema modeling.
- SQL-based business analytics.

## 📚 Learning Resources

This project follows the learning resources from Data With Baraa:

- [Original GitHub Repository](https://github.com/DataWithBaraa/sql-data-warehouse-project)
- [Data Warehouse Project Tutorial](https://youtu.be/9GVqKuTVANE)
