# 📊 Northwind Traders – End-to-End Data Analytics & Power BI Dashboard

## 📌 Project Overview

Northwind Traders is a fictional wholesale organization that imports and exports specialty food products across international markets.

This project demonstrates an end-to-end data analytics workflow, transforming raw Northwind transactional data into meaningful business insights through SQL analysis, data cleaning, data modeling, and interactive Power BI dashboards.

The project focuses on five key business areas:

- Sales Performance
- Customer Behavior
- Inventory Trends
- Employee Productivity
- Supplier Contributions

---

# 🎯 Project Objective

The objective of this project is to create a visually appealing, interactive, and user-friendly Power BI report that effectively communicates key performance metrics and business insights.

The report consolidates data from multiple relational tables to provide a comprehensive view of:

- Sales performance
- Customer behavior
- Inventory efficiency
- Employee productivity
- Supplier contributions

Interactive visualizations, slicers, and filters allow users to explore the data dynamically.

---

# 🗂️ Dataset Overview

The dataset used in this project is the **Northwind Traders database**, which represents the operational and sales data of a fictional wholesale company.

The data is stored in CSV format and follows a relational database structure.

## Tables Used

- Customers
- Employees
- Orders
- Order Details
- Products
- Suppliers
- Shippers
- Categories

These tables are connected using primary and foreign key relationships, enabling integrated analysis across different business domains.

---

# 🛠️ Tools & Technologies

- **SQL**
- **MySQL Workbench**
- **Microsoft Excel**
- **Power Query**
- **Power BI**
- **DAX**

---

# 🔄 Project Workflow

The project followed a structured end-to-end analytics workflow:

1. Data collection from CSV files
2. Data import into Power BI
3. Data cleaning and transformation using Power Query
4. Data validation and consistency checks
5. Data modeling using table relationships
6. SQL-based exploratory analysis
7. Dashboard design and visualization
8. Business insight generation and interpretation

---

# 🧹 Data Cleaning & Transformation

Data cleaning and transformation were performed using **Power Query** to improve data quality, consistency, and usability.

## Issues Identified

- Missing values in Region, Fax, and shipping-related fields
- Unnecessary columns not required for analysis
- Columns containing approximately 1–3% missing values
- Incorrect data types in date columns

## Cleaning Actions

- Missing Region and Fax values were replaced with the standardized value **"Unknown"** where applicable.
- The **Picture** column was removed from the Categories table because it was not required for analysis.
- **Photo** and **Notes** columns were removed from the Employees table.
- Rows containing approximately 1–3% missing values in selected fields were removed where appropriate.
- The **Homepage** column was removed from the Suppliers table.
- Incorrect data types were corrected.

These transformations simplified the dataset and prepared it for reliable analysis and visualization.

---

# ✅ Data Validation

After data cleaning, validation checks were performed to ensure data accuracy and consistency.

### Validation Steps

- Compared row counts before and after cleaning
- Verified relationships between tables
- Validated numerical fields
- Validated date fields
- Checked overall data consistency

These checks helped ensure that the cleaned dataset was suitable for analytical reporting.

---

# 📊 Power BI Report

The Power BI report consists of **five interactive dashboards**, with each dashboard focusing on a specific business function.

---

## 1. 📈 Sales Performance Overview

![Sales Performance Overview](screenshots/sales-performance-overview.png)

Provides a high-level view of sales performance, total revenue, total orders, monthly revenue trends, and country-level performance.

### Key Analysis

- Total Revenue
- Total Orders
- Monthly Revenue Trends
- Revenue by Country
- Revenue by Product Category
- Top-Performing Countries
- Sales Performance Trends

---

## 2. 👥 Customer Analytics Overview

![Customer Analytics Overview](screenshots/customer-analytics-overview.png)

Analyzes customer behavior and geographic distribution, highlighting customer segments and regions contributing to overall sales.

### Key Analysis

- Customer Distribution
- Customer Segmentation
- Customer Geographic Distribution
- Customer Revenue Contribution
- Customer Order Patterns
- Regional Customer Analysis

---

## 3. 📦 Inventory Trends Overview

![Inventory Trends Overview](screenshots/inventory-trends-overview.png)

Monitors product inventory and sales patterns to support inventory planning and stock management.

### Key Analysis

- Product Stock Levels
- Units Sold
- Inventory Trends
- Inventory Turnover
- Product Sales Patterns
- High-Demand Products
- Category-Level Inventory Analysis

---

## 4. 👩‍💼 Workforce Analytics

![Workforce Analytics](screenshots/workforce-analytics.png)

Evaluates employee performance by examining order handling, productivity, and operational contribution.

### Key Analysis

- Employee Order Handling
- Employee Productivity
- Orders by Employee
- Employee Contribution
- Employee Performance Analysis
- Workforce Distribution

---

## 5. 🚚 Supplier Performance Analytics

![Supplier Performance Analytics](screenshots/supplier-performance-analytics.png)

Provides insights into supplier contributions and product supply patterns, helping understand supplier dependency and product availability.

### Key Analysis

- Supplier Contribution
- Supplier Distribution
- Products by Supplier
- Supplier Geographic Distribution
- Supplier Product Supply
- Supplier Performance Analysis

---

# 🔍 SQL Analysis

SQL analysis was performed using **MySQL Workbench** to explore business questions across customers, products, orders, employees, and suppliers.

## 👥 Customer Analysis

- Average number of orders per customer
- High-value repeat customers
- Customer order patterns by city and country
- Customer total spending
- Customer order frequency
- Preferred product categories
- Customer frequency segmentation

## 📦 Product & Sales Analysis

- Revenue by category
- Revenue by product
- Country and category performance
- Product price bands
- Stock versus sales analysis
- Seasonal demand
- Monthly product sales anomalies

## 👩‍💼 Employee Analysis

- Employee geographic distribution
- Employee title distribution
- Employee hiring trends
- Employee courtesy-title distribution

## 🚚 Supplier Analysis

- Supplier geographic distribution
- Supplier distribution by category
- Supplier pricing
- Supplier categories by region

---

# 💡 Key Business Insights

### 🌎 Revenue Concentration by Country

The United States and Germany generate a significant portion of total revenue, highlighting their importance to overall business performance.

### 🥤 Top-Performing Product Categories

Beverages and Dairy Products contribute a large share of sales and are important areas for inventory management and sales analysis.

### 👥 Customer Revenue Distribution

A relatively small group of customers contributes a large percentage of total sales, highlighting the importance of understanding high-value customer behavior.

### 👩‍💼 Employee Productivity Differences

Employees handle different numbers of orders, providing insights into workforce productivity and operational efficiency.

### 🚚 Supplier Dependency

A limited number of suppliers provide a large proportion of products. Understanding supplier contribution helps monitor supplier dependency and potential supply-chain risks.

---

# 💡 Skills Demonstrated

- SQL
- MySQL Workbench
- Exploratory Data Analysis
- Excel
- Power Query
- Power BI
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Data Visualization
- Business Intelligence
- Business Analysis

---

# 📁 Project Structure

```text
northwind_business_intelligence_analysis/
│
├── 01_dataset/
│   ├── categories.csv
│   ├── customers.csv
│   ├── employees.csv
│   ├── order_details.csv
│   ├── orders.csv
│   ├── products.csv
│   ├── shippers.csv
│   └── suppliers.csv
│
├── 02_MECE_breakdown/
│   ├── Northwind_PowerBI_Dashboard_Documentation.docx
│   
│
├── 03_sql_scripts/
│   ├── northwind_eda_queries.sql
│   
│
├── 04_excel_analysis/
│   ├── northwind_traders_excel_analysis.xlsx
│   
│
├── 05_powerbi_report/
│   ├── northwind_sales_analysis_report.pbix
│   
│
├── 06_executive_dashboard/
│   ├── Northwind_Traders_Executive_Dashboard_Report.pbix
│   
│
├── 07_project_presentation/
│   ├── northwind_sales_analysis_presentation.pptx
│   
│
├── screenshots/
│   ├── sales-performance-overview.png
│   ├── customer-analytics-overview.png
│   ├── inventory-trends-overview.png
│   ├── workforce-analytics.png
│   └── supplier-performance-analytics.png
│
└── README.md

