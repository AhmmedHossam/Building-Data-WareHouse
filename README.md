# Building-Data-WareHouse
Welcome to the Data Warehouse and Analytics Project repository! 🚀
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights.

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
1- Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2-Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3- Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

![data_architecture](https://github.com/user-attachments/assets/b49cb615-28d7-425c-b535-22293ac37e24)

# This project involves:

1-Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.

![download](https://github.com/user-attachments/assets/f94d24e4-1de1-437c-b1de-71fc8bc41602)
![download (1)](https://github.com/user-attachments/assets/1b872a51-acac-4b36-8559-a6a2b6a58543)


2-ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.

![ETL](https://github.com/user-attachments/assets/8008aff4-c7c0-4722-becf-ae10ce129164)
![data_integration](https://github.com/user-attachments/assets/721defd9-c45b-4565-bccf-1ed324ad08e1)

3-Data Modeling: Developing fact and dimension tables optimized for analytical queries.
![data_model](https://github.com/user-attachments/assets/98b0dc9d-45a3-4c9d-802f-4c9a47f27512)

4-Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

# 🚀 Project Requirements

Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.


# BI: Analytics & Reporting (Data Analysis)

Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.
