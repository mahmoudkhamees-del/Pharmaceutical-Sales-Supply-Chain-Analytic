💊 Pharmaceutical Sales & Supply Chain Analytics

📌 Project Overview

This project focuses on analyzing pharmaceutical sales, inventory performance, and supply chain operations using SQL Server and Microsoft Power BI.

The goal is to transform raw data into meaningful business insights that help stakeholders understand sales performance, evaluate product demand, monitor inventory levels, and explore supplier and warehouse performance.

The project combines sales analysis with inventory and supply chain analytics through interactive dashboards designed to support data-driven decision-making.

🎯 Business Objectives

* Analyze sales performance across products, product classes, customers, countries, and sales channels.
* Identify top-selling products and high-contributing customers.
* Track sales trends over time and compare product performance.
* Monitor inventory value and inventory levels across warehouses.
* Evaluate inventory levels against forecast demand.
* Analyze supplier performance and average lead times.
* Build interactive dashboards that make business insights easier to explore.

🛠️ Tools & Technologies

* SQL Server: Data exploration, data validation, and analytical queries.
* Microsoft Power BI: Interactive dashboard development and data visualization.
* Power Query: Data preparation and transformation.
* DAX: Measures and business KPIs.
* Data Modeling: Relationships between tables to support analytical reporting.

📊 Dashboard Structure

The Power BI report consists of four pages, each designed to answer a different set of business questions.

1. Executive Overview

Provides a high-level summary of overall business performance.

Key metrics and visuals:

* Total Sales
* Total Customers
* Total Products
* Total Suppliers
* Total Inventory Value
* Average Lead Time
* Sales Trend Over Time
* Sales by Product Class
* Sales by Channel
* Top Customers
* Units Sold

Business questions:

* How are sales performing over time?
* Which product classes contribute most to sales?
* How are sales distributed across channels?
* Which customers contribute most to total sales?

2. Sales Analysis

Focuses on detailed sales performance and customer contribution.

Key metrics and visuals:

* Total Sales
* Total Customers
* Total Products
* Total Quantity Sold
* Average Selling Price
* Sales YTD
* Monthly Sales Trend
* Top Customers
* Sales by Product Class
* Sales by Sales Team
* Top-Selling Products

Business questions:

* Which products generate the highest sales?
* Who are the top-contributing customers?
* How does sales performance change over time?
* How do product classes and sales teams compare?

3. Inventory Analysis

Examines inventory levels, inventory value, demand, and supply chain performance.

Key metrics and visuals:

* Inventory Value
* Average Inventory Level
* Average Reorder Point
* Average Lead Time
* Forecast Demand
* Total Warehouses
* Inventory Value Trend
* Highest-Inventory SKUs
* Inventory by Warehouse
* Supplier Performance
* Demand vs. Inventory

Business questions:

* How does inventory value change over time?
* Which products hold the highest inventory levels?
* How is inventory distributed across warehouses?
* How does forecast demand compare with inventory levels?
* How do suppliers compare in terms of lead time?

4. Product & Customer Insights

Provides a more detailed view of product performance and customer contribution.

Key metrics and visuals:

* Total Products
* Total Customers
* Total Sales
* Average Sales per Product
* Top Customer
* Top Product
* Sales by Country
* Sales Distribution by Product Class
* Product Hierarchy Performance
* Product Class Sales Contribution
* Top Customers
* Top-Selling Products

Business questions:

* Which products and product classes contribute most to sales?
* Which customers generate the highest sales?
* How is sales performance distributed across countries?
* How do products compare in sales, quantity, and inventory value?

📈 Key Performance Indicators (KPIs)

The report includes business metrics covering sales, customers, products, and inventory.

KPI	Purpose
Total Sales	Measures overall sales performance.
Total Quantity Sold	Tracks the quantity of products sold.
Total Customers	Measures the number of customers represented in the data.
Total Products	Measures the number of products represented in the data.
Average Selling Price	Evaluates the average selling price based on the underlying calculation.
Sales YTD	Tracks year-to-date sales performance.
Inventory Value	Measures the monetary value of inventory.
Average Inventory Level	Summarizes inventory levels.
Average Reorder Point	Summarizes the reorder-point values in the dataset.
Average Lead Time	Measures the average supplier lead time.
Forecast Demand	Summarizes forecast demand.

Note: KPI definitions and aggregation methods depend on the underlying data structure and DAX measure definitions.

🔍 Data Analysis Workflow

The project follows a structured analytical workflow:

1. Data Import: Loaded the source tables into SQL Server.
2. Data Profiling: Explored the structure, fields, and characteristics of the available data.
3. Data Quality Checks: Investigated data quality and validated relevant fields.
4. SQL Analysis: Used SQL queries to explore the data and investigate business questions.
5. Data Preparation: Prepared and transformed data for reporting.
6. Data Modeling: Configured table relationships to support analysis in Power BI.
7. DAX Measures: Developed measures to calculate business KPIs.
8. Dashboard Development: Designed interactive report pages with charts, tables, KPI cards, and slicers.
9. Visual Analysis: Organized visuals around business questions to make the report easier to interpret.

🎛️ Interactive Features

The report includes interactive slicers that allow users to explore the data by selected dimensions, including:

* Year
* Month
* Product Class
* Country
* Channel
* Distributor
* Warehouse, where applicable

These controls help users investigate performance across different business segments.

💡 Business Value

This project demonstrates how data analysis can support pharmaceutical sales and supply chain decision-making by helping users:

* Identify high-performing products and customers.
* Compare sales performance across business dimensions.
* Monitor inventory distribution and value.
* Explore the relationship between forecast demand and inventory levels.
* Compare supplier lead times.
* Navigate business performance through interactive dashboards.

The report is intended to support exploratory analysis and operational monitoring. Business decisions should also consider data quality, business rules, and the limitations of the underlying dataset.

⚠️ Data & Interpretation Notes

* The analysis is based on the fields and records available in the project datasets.
* KPI values depend on the definitions, aggregation methods, and filter context used in the report.
* Inventory levels and forecast demand are not necessarily directly comparable unless their units, time periods, and aggregation methods are aligned.
* Supplier lead time is not, by itself, a complete measure of supplier performance.
* Results should be interpreted in the context of the available data.

🚀 Skills Demonstrated

* SQL-based data exploration and validation
* Data cleaning and preparation
* Data modeling and table relationships
* DAX measures and KPI development
* Sales performance analysis
* Inventory and supply chain analytics
* Interactive dashboard design
* Data visualization and business reporting
* Translating business questions into analytical views

📷 Project Screenshots

Screenshots of the dashboard pages can be added here.

Suggested structure:

* screenshots/executive-overview.png
* screenshots/sales-analysis.png
* screenshots/inventory-analysis.png
* screenshots/product-customer-insights.png

👤 Author

Mahmoud Khamees

Aspiring Data Analyst | SQL Server | Power BI | Data Analytics

* LinkedIn: [https://www.linkedin.com/in/mahmoud-khamees-6a3776362?utm_source=share_via&utm_content=profile&utm_medium=member_ios]
* GitHub: [https://github.com/mahmoudkhamees-del]

⸻

This project was developed as a practical data analytics portfolio project to demonstrate the application of SQL Server and Power BI to pharmaceutical sales and supply chain analysis.