SQL Data Warehouse Project
Overview
A SQL Server data warehouse that integrates CRM and ERP data through a three-layer architecture: Bronze, Silver, and Gold. The project includes ETL pipelines, data quality checks, star schema modeling, and SQL-based analysis.
Architecture
- Bronze: Loads raw CSV data into SQL Server.
- Silver: Cleans, standardizes, and prepares the data.
- Gold: Stores business-ready fact and dimension tables for analytics.

<img width="6235" height="3216" alt="data_architecture" src="https://github.com/user-attachments/assets/44e078e5-a0b4-4844-9a02-08cbbb0dcafb" />
  
Data Model
The Gold layer uses a star schema with:
- gold.fact_sales
- gold.dim_customers
- gold.dim_products

<img width="6033" height="2249" alt="data_model" src="https://github.com/user-attachments/assets/9b459be6-8098-4f72-b423-fc2fa2911d1d" />

Analysis
The project includes exploratory data analysis and advanced SQL analytics covering business metrics, trends, running totals, performance, and segmentation. It produces two reports: Customer Report and Product Report.
