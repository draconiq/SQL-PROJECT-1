# SQL-PROJECT-1
SQL Projects 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Data Warehouse and Analytics Project 🚀

Welcome to the **Data Warehouse and Analytics Project** repository!

This project demonstrates a complete data warehousing and analytics solution, from building a data warehouse to generating actionable business insights. It is designed as a portfolio project to showcase industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture**, consisting of Bronze, Silver, and Gold layers.

![Data Architecture](docs/data_architecture.png)

### Bronze Layer

Stores raw data as-is from the source systems. Data is ingested from CSV files into a SQL Server database.

### Silver Layer

Handles data cleansing, standardization, transformation, and normalization to prepare the data for analysis.

### Gold Layer

Contains business-ready data modeled using a **Star Schema** for reporting and analytics.

---

## 📖 Project Overview

This project includes:

* **Data Architecture:** Designing a modern data warehouse using Bronze, Silver, and Gold layers.
* **ETL Pipelines:** Extracting, transforming, and loading data from source systems.
* **Data Modeling:** Creating fact and dimension tables optimized for analytical queries.
* **Analytics & Reporting:** Developing SQL-based reports to generate actionable business insights.

### 🎯 Skills Demonstrated

* SQL Development
* Data Architecture
* Data Engineering
* ETL Pipeline Development
* Data Modeling
* Data Analytics

---

## 🛠️ Important Links & Tools

Everything used in this project is free.

* **Datasets:** CSV files used as source data.
* **SQL Server Express:** Database server used to host the data warehouse.
* **SQL Server Management Studio (SSMS):** Used to manage databases and execute SQL queries.
* **Git & GitHub:** Used for version control and project management.
* **Draw.io:** Used to design architecture, data models, and data flow diagrams.
* **Notion:** Used for project planning and organization.
* **Notion Project Steps:** Contains all project phases and tasks.

---

## 🚀 Project Requirements

### Building the Data Warehouse — Data Engineering

#### Objective

Develop a modern data warehouse using **SQL Server** to consolidate sales data and enable analytical reporting and informed decision-making.

#### Specifications

* **Data Sources:** Import data from two source systems, ERP and CRM, provided as CSV files.
* **Data Quality:** Clean and resolve data quality issues before analysis.
* **Integration:** Combine both sources into a single analytical data model.
* **Scope:** Focus only on the latest dataset; historical tracking is not required.
* **Documentation:** Provide clear documentation of the data model for business and analytics teams.

---

## 📊 BI: Analytics & Reporting

### Objective

Develop SQL-based analytics to provide insights into:

* Customer Behavior
* Product Performance
* Sales Trends

These insights help stakeholders understand key business metrics and support informed decision-making.

For more details, refer to `docs/requirements.md`.

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Project documentation and diagrams
│   ├── etl.drawio                      # ETL processes and techniques
│   ├── data_architecture.drawio        # Project architecture
│   ├── data_catalog.md                 # Dataset metadata and descriptions
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema data models
│   ├── naming-conventions.md           # Naming standards
│
├── scripts/                            # SQL scripts for ETL
│   ├── bronze/                         # Raw data loading scripts
│   ├── silver/                         # Data cleaning and transformation
│   ├── gold/                           # Analytical data models
│
├── tests/                              # Data quality and testing scripts
│
├── README.md                           # Project overview
├── LICENSE                             # License information
├── .gitignore                          # Git ignored files
└── requirements.txt                    # Project dependencies
```

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share this project with proper attribution.

---

## 🌟 About the Author

Hi there! I'm **Baraa Khatib Salkini**, also known as **Data With Baraa**.

I'm an IT professional and passionate YouTuber focused on sharing knowledge and making data engineering and analytics easier and more enjoyable to learn.

Feel free to connect through:

* YouTube
* LinkedIn
* Website
* Newsletter
* PayPal
