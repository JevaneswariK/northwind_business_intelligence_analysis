# Northwind Traders – End-to-End Data Analytics & Power BI

An end-to-end data analytics project using the **Northwind Traders** dataset to analyze sales, customers, products, inventory, employees, and suppliers.

The project uses **MySQL, Excel, Power Query, and Power BI** to transform raw relational data into business insights and interactive dashboards.

---

## 📌 Project Overview

Northwind Traders is a fictional wholesale company that imports and exports specialty food products across international markets.

The objective of this project is to analyze the company's operational and sales data and build a comprehensive Business Intelligence solution.

The project covers:

- Sales analysis
- Customer analysis
- Product and category analysis
- Inventory analysis
- Employee performance analysis
- Supplier analysis
- Geographic analysis
- Order and revenue trends
- Product demand and anomaly analysis

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **MySQL Workbench** | SQL analysis and Exploratory Data Analysis |
| **Microsoft Excel** | Data analysis and supporting calculations |
| **Power Query** | Data cleaning and transformation |
| **Power BI** | Data modeling, DAX, KPIs and interactive dashboards |

---

## 🗂️ Dataset

The project uses the Northwind Traders relational dataset.

### Tables

- **Customers** – Customer details, contact information and location
- **Employees** – Employee details, titles, hire dates and reporting information
- **Orders** – Order dates, customers, employees and shipping information
- **Order Details** – Products, quantities, prices and discounts for each order
- **Products** – Product information, pricing, inventory and supplier details
- **Suppliers** – Supplier information and location
- **Categories** – Product categories
- **Shippers** – Shipping company information

These tables are connected through primary and foreign key relationships for integrated analysis.

---

# 🔍 MySQL Exploratory Data Analysis

MySQL Workbench was used to perform business-oriented exploratory analysis.

### Customer Analysis

- Average orders per customer
- High-value repeat customers
- Customer order patterns by country and city
- Customer total spending
- Customer order frequency
- Preferred product categories
- Customer segmentation based on order frequency

### Sales & Product Analysis

- Revenue by product category
- Quantity sold by category
- Product sales performance
- Product pricing
- Inventory levels
- Seasonal product demand
- Product sales anomalies

### Employee Analysis

- Employee distribution by country
- Employee distribution by job title
- Employee courtesy title distribution
- Hiring trends by year and title

### Supplier Analysis

- Supplier distribution by country
- Suppliers by product category
- Supplier product counts
- Supplier pricing
- Regional supplier pricing patterns

### Revenue Calculation

Revenue is calculated using:

```text
Revenue = Quantity × Unit Price × (1 - Discount)

---

📊 Excel Analysis

Excel was used as an additional analysis and validation layer.
The Excel analysis supports:

Data exploration
Business calculations
Trend analysis
Data validation
Supporting analysis for the Power BI report

---

🧹 Data Cleaning & Transformation

Power Query was used to prepare the data for Power BI.
Key transformations included:

Handling missing values
Replacing blank Region values with Unknown
Removing unnecessary columns
Removing the unused Categories Picture column
Removing unnecessary Employees Photo and Notes columns
Removing the Suppliers Homepage column
Correcting data types
Validating table relationships
Performing data consistency checks

The cleaned data was then used for data modeling and dashboard development.

---

# 📊 Power BI Dashboards

## 1. Sales Performance Overview

![Sales Performance Overview](screenshots/sales-performance-overview.png)

The Sales Performance dashboard provides an overview of sales and revenue performance.

**Key Analysis:**
- Total Revenue
- Top 20% Revenue Share
- Average Order Value
- Highest Revenue Category
- Revenue by Product Category
- Revenue vs Discount
- Revenue trends over time


## 2. Customer Analytics Overview

![Customer Analytics Overview](screenshots/customer-analytics-overview.png)

The Customer Analytics dashboard analyzes customer behavior and geographic distribution.

**Key Analysis:**
- Total Customers
- High Value Customers %
- Customer Lifetime Value
- Customer Retention Rate
- Customers by Contact Title
- Customer Distribution by Segment
- Customer Distribution by Country
- Top Customers by Revenue


## 3. Inventory Trends Overview

![Inventory Trends Overview](screenshots/inventory-trends-overview.png)

The Inventory Trends dashboard analyzes inventory levels and product movement.

**Key Analysis:**
- Active Categories
- Total Units in Stock
- Total Units Sold
- Inventory Turnover
- Sales vs Stock by Category
- Stock Coverage by Category
- Units Sold and Turnover by Category
- Top 5 Revenue Products


## 4. Workforce Analytics

![Workforce Analytics](screenshots/workforce-analytics.png)

The Workforce Analytics dashboard analyzes employee productivity and operational performance.

**Key Analysis:**
- Performance Index
- On-Time Deliveries %
- Average Order Processing Time
- Total Revenue by Employee
- Average Performance Index by Role
- Employee Order Volume


## 5. Supplier Performance Analytics

![Supplier Performance Analytics](screenshots/supplier-performance-analytics.png)

The Supplier Performance dashboard analyzes supplier contribution, pricing and distribution.

**Key Analysis:**
- Total Suppliers
- Average Delivery Delay
- Average Shipping Time
- Top Supplier Contribution
- Revenue by Supplier
- Average Unit Price by Supplier
- Total Products by Supplier
- Supplier Distribution by Country

---

📌 Key Business Insights

The analysis identified several important business patterns:

The United States and Germany contribute a significant portion of overall revenue.
Beverages and Dairy Products are important revenue-generating categories.
A relatively small group of customers contributes a significant share of total sales.
Employee order-handling volumes vary across employees.
A limited number of suppliers contribute a significant proportion of products.
Product demand and sales performance vary across categories and time periods.

---

🎯 Business Questions Addressed

The project was designed to answer questions including:

Customers
What is the average number of orders per customer?
Are there high-value repeat customers?
How do customer order patterns vary by city or country?
What are the different customer order-frequency segments?
What are customers' preferred product categories?

Products & Sales
Which product categories contribute most to revenue?
Which products have the highest sales volume?
How does product demand change across months or seasons?
Are there anomalies in product sales performance?
How are pricing, inventory and sales related?

Employees
What is the geographic and title-wise distribution of employees?
What trends exist in employee hiring dates?
What patterns exist between employee titles and courtesy titles?
How does employee order volume and revenue contribution vary?

Suppliers
What are the regional trends in supplier distribution and pricing?
How are suppliers distributed across product categories?
How do supplier pricing and categories vary across regions?

---

📁 Project Structure
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

---

💡 Skills Demonstrated

SQL
MySQL Workbench
Exploratory Data Analysis
Excel
Power Query
Power BI
DAX
Data Cleaning
Data Transformation
Data Modeling
KPI Development
Data Visualization
Business Intelligence
Business Analysis

👩‍💻 Author
Jevaneswari K
Data Analytics | SQL | Excel | Power BI

⭐ Project Summary
This project demonstrates an end-to-end Business Intelligence workflow, starting from raw relational data and SQL-based analysis through Excel and Power Query, and finally delivering interactive Power BI dashboards for business reporting and decision support.
