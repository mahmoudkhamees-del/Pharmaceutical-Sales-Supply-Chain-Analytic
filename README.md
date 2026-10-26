Pharmaceutical Sales & Supply Chain Analytics

An end-to-end data analytics portfolio project exploring pharmaceutical sales performance, product and customer insights, inventory levels, and supply chain operations using SQL Server and Microsoft Power BI.

The project transforms two separate datasets into interactive dashboards designed to support business performance monitoring, inventory analysis, and data-driven decision-making.

Project Overview

Pharmaceutical sales and inventory management involve different analytical challenges. Sales analysis helps identify revenue contributors, customer purchasing patterns, and product performance, while inventory and supply chain analysis helps monitor stock levels, warehouse distribution, forecast demand, and supplier lead times.

This project addresses these analytical needs through two distinct datasets:

* Pharmaceutical Sales Dataset: Used to analyze sales performance, customers, products, sales channels, and geographic distribution.
* Supply Chain & Inventory Dataset: Used to analyze inventory value, inventory levels, reorder points, forecast demand, warehouses, and supplier lead times.

The datasets are analyzed as separate analytical domains. They are not assumed to represent the same company, and their measures are not treated as directly comparable unless a valid business and data relationship has been established.

The final Power BI report contains four interactive pages, each designed to answer a different set of business questions.

Project Objectives

The project aims to:

* Analyze sales performance over time.
* Identify top-selling products and high-contributing customers.
* Compare sales performance across product classes, countries, and sales channels.
* Examine product-level sales and quantity patterns.
* Monitor inventory value and stock levels.
* Compare inventory levels with forecast demand.
* Analyze inventory distribution across warehouses.
* Compare suppliers using available lead-time information.
* Build interactive dashboards that communicate business performance clearly.
* Apply SQL-based analysis and data validation before developing Power BI reports.

Tools & Technologies

Tool	Purpose
SQL Server	Data exploration, validation, and analytical queries
SQL	Aggregation, filtering, joins, and business analysis
Microsoft Power BI	Interactive dashboards and business reporting
Power Query	Data preparation and transformation
DAX	Measures, KPIs, and analytical calculations
Data Modeling	Table relationships and analytical model design
GitHub	Project documentation and portfolio presentation

Data Sources & Scope

The project uses two separate datasets.

1. Pharmaceutical Sales Dataset

This dataset supports analysis of:

* Sales performance
* Product classes and individual products
* Customer contribution
* Sales channels
* Country-level sales distribution
* Sales trends over time
* Sales quantity and average selling price

2. Supply Chain & Inventory Dataset

This dataset supports analysis of:

* Inventory value
* Inventory levels
* Reorder points
* Forecast demand
* Warehouse distribution
* Supplier lead times
* Inventory trends
* Inventory and forecast-demand comparisons

Important Data Scope Consideration

The two datasets are treated as separate analytical domains because they do not represent a confirmed, unified company dataset.

Consequently, sales and inventory measures should be interpreted within their respective data contexts. A combined business conclusion requires appropriate relationships, compatible definitions, and consistent aggregation logic.

The analysis is limited to the fields and records available in the source datasets.

Analytical Workflow

The project follows a structured data analytics workflow:

1. Data Import: Loaded the source tables into SQL Server.
2. Data Profiling: Examined table structures, columns, data types, and available values.
3. Data Quality Checks: Investigated data issues and validated relevant fields.
4. SQL Analysis: Used SQL queries to explore the datasets and answer business questions.
5. Data Preparation: Prepared the data for reporting and visualization.
6. Data Modeling: Configured relationships between relevant tables in Power BI.
7. DAX Development: Created measures for business KPIs and analytical calculations.
8. Dashboard Development: Built four interactive report pages.
9. Visual Analysis: Organized charts, matrices, KPI cards, and filters around business questions.
10. Documentation: Prepared project documentation to explain the analytical approach, dashboard structure, and limitations.

Power BI Dashboard

The report contains four pages.

Page 1 — Executive Overview

Purpose: Provide a high-level overview of sales performance and selected supply chain indicators.

Key metrics and visuals include:

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

* How does sales performance change over time?
* Which product classes contribute most to sales?
* How are sales distributed across channels?
* Which customers contribute most to sales?
* What are the headline inventory and lead-time indicators?

Page 2 — Sales Analysis

Purpose: Examine sales performance, product contribution, customer contribution, and sales trends in greater detail.

Key metrics and visuals include:

* Total Sales
* Total Customers
* Total Products
* Total Quantity Sold
* Average Selling Price
* Sales Year-to-Date (YTD)
* Monthly Sales Trend
* Top Customers
* Sales by Product Class
* Sales by Sales Team
* Top-Selling Products

Business questions:

* Which products generate the highest sales?
* Which customers contribute most to total sales?
* How does sales performance change over time?
* How do product classes compare?
* How is sales distributed across the available sales-team categories?

Page 3 — Inventory Analysis

Purpose: Explore inventory levels, inventory value, warehouse distribution, forecast demand, and supplier lead times.

Key metrics and visuals include:

* Inventory Value
* Average Inventory Level
* Average Reorder Point
* Average Lead Time
* Forecast Demand
* Total Warehouses
* Inventory Value Trend
* Highest-Inventory SKUs
* Inventory by Warehouse
* Supplier Performance by Lead Time
* Demand vs. Inventory

Business questions:

* How does inventory value change over time?
* Which SKUs have the highest inventory levels or values?
* How is inventory distributed across warehouses?
* How does forecast demand compare with available inventory?
* Which suppliers have shorter or longer average lead times?

Page 4 — Product & Customer Insights

Purpose: Provide a more detailed view of product performance, customer contribution, and geographic sales distribution.

Key metrics and visuals include:

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
* How is sales distributed across countries?
* How do products compare in sales, quantity, and inventory value?

Key Performance Indicators

The report includes measures covering sales, customers, products, and inventory.

KPI	Analytical Purpose
Total Sales	Measures sales value within the applicable filter context
Total Quantity Sold	Measures the quantity sold
Total Customers	Counts customers according to the implemented measure
Total Products	Counts products according to the implemented measure
Average Selling Price	Evaluates average selling price using the underlying calculation
Sales YTD	Measures year-to-date sales where supported by the date model
Inventory Value	Measures the monetary value of inventory
Average Inventory Level	Summarizes inventory levels using the implemented calculation
Average Reorder Point	Summarizes reorder-point values
Average Lead Time	Measures the average supplier lead time
Forecast Demand	Summarizes forecast demand
Total Warehouses	Counts warehouses represented in the inventory dataset

Note: The exact definitions of these KPIs depend on the implemented DAX measures, source fields, and filter context. Counts, averages, and totals should be validated against the underlying data before being interpreted as business results.

Interactive Features

The report uses interactive slicers to help users explore the available data.

Depending on the page and applicable dataset, these include:

* Year
* Month
* Product Class
* Country
* Channel
* Distributor
* Warehouse
* Supplier
* SKU or product

The slicers allow users to investigate performance across selected time periods and business dimensions.

Filter interactions should be interpreted according to the relationships and configuration of each visual in the Power BI model.

Data Modeling & Analytical Considerations

The project applies data modeling principles to organize the available tables for analytical reporting.

The modeling workflow includes:

* Reviewing table structures and available keys.
* Examining relationships between tables.
* Configuring relationships needed for analysis.
* Developing measures for relevant business KPIs.
* Using filter context to support interactive reporting.
* Validating aggregations and results against the source data.

Because the sales and inventory datasets are separate, their measures should not be combined into a single business calculation without a justified relationship and compatible definitions.

Business Value

The dashboards demonstrate how data analysis can support business questions related to pharmaceutical sales and supply chain operations.

Potential applications include:

* Identifying high-contributing products and customers.
* Comparing sales across product classes, countries, and channels.
* Monitoring sales trends over time.
* Understanding inventory distribution across warehouses.
* Comparing inventory levels with forecast demand.
* Reviewing reorder-point information.
* Investigating supplier lead-time differences.

These are analytical use cases rather than claims of measured financial improvement. Specific recommendations should be based on validated findings from the underlying data.

Data Limitations

The following limitations should be considered when interpreting the report:

* The project uses two separate datasets rather than a confirmed, unified company dataset.
* The available fields determine which business questions can be answered.
* KPI values depend on measure definitions, aggregation methods, and filter context.
* Inventory levels and forecast demand should only be compared when their units and time periods are compatible.
* Average lead time alone does not fully measure supplier performance.
* Reorder points should be interpreted in the context of the underlying inventory methodology.
* Sales and inventory measures should not be combined into unsupported business conclusions.
* Results should be validated against the source data before being used to make operational decisions.

Skills Demonstrated

SQL & Data Analysis

* Data exploration
* Data profiling and validation
* Analytical queries
* Aggregation and filtering
* Business-question-driven analysis

Power BI

* Data modeling
* DAX measures and KPI development
* Interactive dashboard development
* Slicers and filter interactions
* Matrix and hierarchy analysis
* Comparative and trend visualizations

Business Intelligence

* Sales performance analysis
* Product and customer analysis
* Inventory analysis
* Supply chain reporting
* KPI interpretation
* Dashboard storytelling
* Business reporting and visualization

Repository Structure

The repository currently contains the project README.

Recommended structure for the completed portfolio project:

Pharmaceutical-Sales-Supply-Chain-Analytic/
│
├── README.md
│
├── screenshots/
│   ├── executive-overview.png
│   ├── sales-analysis.png
│   ├── inventory-analysis.png
│   └── product-customer-insights.png
│
├── sql/
│   └── analytical-queries.sql
│
└── powerbi/
    └── pharmaceutical-sales-supply-chain.pbix

The folders and filenames above are recommended. Add them only when the corresponding files are available and ready to share.

How to Explore the Project

1. Review the dashboard screenshots in the screenshots folder.
2. Read the dashboard descriptions and business questions in this README.
3. Review the SQL queries if they are included in the repository.
4. Open the Power BI report if the .pbix file is available.
5. Explore the slicers and visuals to investigate the available data.

If the Power BI report uses local source-file paths, those paths may need to be updated before refreshing the data.

Author

Mahmoud Khamees

Data Analytics Portfolio Project

Focus Areas: SQL Server | Microsoft Power BI | DAX | Data Modeling | Business Intelligence

* GitHub: https://github.com/mahmoudkhamees-del
* LinkedIn: https://www.linkedin.com/in/mahmoud-khamees-6a3776362/

Disclaimer

This project was developed for educational and portfolio purposes. Its findings and metrics are based on the available datasets and implemented calculations. They should not be interpreted as verified results for a specific pharmaceutical company.

The analysis demonstrates the application of SQL Server and Power BI to sales and supply chain analytics.