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

