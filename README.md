🚀 End-to-End SQL Data Warehouse & Power BI Analytics Project

This project demonstrates a full modern BI workflow — from raw data → SQL data warehouse → ETL → star schema modeling → Power BI dashboards.


⭐ PROJECT HIGHLIGHTS

✔ Built a complete SQL Data Warehouse 

✔ Designed ETL pipeline (Extract → Transform → Load)

✔ Implemented Fact & Dimension tables (Star Schema)

✔ Created 3 professional Power BI dashboards

✔ Used DAX measures, relationships, and modeling

✔ Delivered actionable business insights


🧱 Architecture Overview
Raw Data → Staging Tables → Data Cleaning & Transformation
         → Fact & Dimension Tables (Star Schema)
         → Power BI Dashboards (Product, Customer, Revenue)

 
🗃️ Data Warehouse Design

⭐ Fact Table

fact_sales

• Revenue

• Quantity

• Profit

• Order Date

• Product Key

• Customer Key

⭐ Dimension Tables

Table                             Description

dim_customers                     Customer profile, age, location, segments

dim_products	                Product category, price, cost

dim_date	                         Calendar table for time intelligence

dim_segments	                Customer segmentation logic

🧠 Key Modeling Concepts Used

• Surrogate Keys

• Star Schema

• Slowly Changing Dimensions (basic form)

• Data Normalization

• Relationship Mapping in Power BI

🔄 ETL Pipeline (SQL)

1. Extract

Load raw data into staging tables.

2. Transform

• Clean nulls, duplicates

• Convert data types

• Standardize categories

• Add calculated fields: revenue, profit, AOV

3. Load

Populate Fact & Dimension tables in correct order:

dim_date → dim_products → dim_customers → fact_sales

📊 Power BI Dashboards

1️⃣ Product Performance Dashboard

Business Insights Delivered:

• Best-selling products

• Most profitable products

• Category-wise revenue

• Performance segmentation (Low/Mid/High)

• Revenue vs Average Selling Price


2️⃣ Customer Insights Dashboard

Key Insights:

• CLV (Customer Lifetime Value)

• Repeat customers vs New customers

• Retention and churn

• RFM-style segmentation

• Customer demographics


3️⃣ Revenue Deep Dive Dashboard

Insights:

• YoY Growth %

• Monthly revenue trends

• Average order value (AOV)

• Age-group revenue

• Revenue by customer segment


🛠️ Technologies Used

• SQL (MySQL / SQL Server style)

• Power BI

• Power Query

• DAX

• ETL Pipeline Design

• Star Schema Modeling

• Data Cleaning & Transformation


🎯 Key Outcomes

• Converted raw messy data into a clean analytical model

• Built dashboards used for product, customer, and revenue insights

• Created a warehouse that supports enterprise-level reporting

• Designed analytics that answer real business questions

• Demonstrated full-stack BI capability (SQL → ETL → Model → Dashboard → Insights)



Just tell me!
