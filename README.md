# Data Warehouse and Analytics Project
## Acknowledgments  
This project was inspired by [Data Engineering Project: Data Warehouse End to End Project using SQL](https://www.youtube.com/watch?v=9GVqKuTVANE) on YouTube.

This repository demonstrates the end-to-end process of building a Data Warehouse (DWH) using SQL. The project covers planning, architecture, ETL pipeline development, and data modeling with a layered approach (Bronze → Silver → Gold).

## Project Overview
+ Planned and documented requirements using Notion and Draw.io.
+ Designed a multi-layer data architecture (Bronze, Silver, Gold).
+ Implemented ETL pipelines with SQL scripts and stored procedures.
+ Built a Star Schema model for analytics.
+ Version controlled all work with Git.

## Architecture and Diagrams
### Data Warehouse Architecture
<p center="align">
  <img width="1051" height="561" alt="DataWarehouse drawio" src="https://github.com/user-attachments/assets/9370ce41-c1da-4f43-9029-abfa83e18755" />
</p>

This diagram shows the overall layered DWH design (Bronze, Silver, Gold). The Bronze layer ingests raw data, the Silver layer cleans and standardizes it, and the Gold layer organizes it into business-friendly models for analytics.

### ETL Data Flow
<p center="align">
  <img width="936" height="611" alt="DataFlow drawio" src="https://github.com/user-attachments/assets/b2d98465-5059-4447-a94e-fe69b41e61cc" />
</p>

This flow chart illustrates how data moves through the pipeline: from raw ingestion in Bronze → transformation and cleansing in Silver → structured and modeled in Gold. Each arrow represents ETL jobs and stored procedures that automate the pipeline.

### Sales Data Mart (Star Schema)
<p center="align">
  <img width="891" height="521" alt="SalesDataMart drawio" src="https://github.com/user-attachments/assets/74f40b77-d4c0-4f30-9f64-688d8453c92d" />
</p>

This star schema shows the Sales Fact table linked to Dimension tables (Customers and Products). It enables efficient querying for business KPIs such as sales by customer, region, or product category.

## Skills and Tools Demonstrated
+ SQL Development: DDL, DML, Stored Procedures
+ Data Warehouse Design: Layered architecture, ETL pipelines
+ Data Modeling: Facts, Dimensions, Star Schema
+ Documentation & Planning: Notion, Draw.io, Git
