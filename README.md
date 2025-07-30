# 📊 Northwind Traders Excel Dashboard – Business Insights Project

### Overview
This project uses the fictional Northwind Traders dataset, which can be accessed through [Maven Analytics] (https://app.mavenanalytics.io/datasets?search=north), to replicate business analysis in the real world. It aims at developing a detailed Excel dashboard to provide practical information on some of the major business operations like sales, customer behavior, product performance, employee productivity, and shipping logistics.

### 📌 Motivation
In a global trading environment, businesses rely on real-time insights to track sales performance, understand customer behavior, monitor logistics, and evaluate internal productivity. I wanted to simulate this real-world scenario and sharpen my analytical and dashboarding skills by working with the fictional Northwind dataset, which provides a comprehensive model of a trading business.

### 🎯 Objective
To design a dynamic and insightful Excel dashboard that delivers actionable business intelligence across key areas including sales, customer relationships, product performance, employee productivity, and shipping operations.
### 🧭 Scope
This project covers multiple functional aspects of the Northwind operation:
- Sales and order transactions
- Product categories and performance
- Customer segmentation
- Employee sales efficiency
- Shipping and logistics metrics

The dashboard is fully interactive, with slicers and timeline filters, making it easy for decision-makers to explore the data and uncover trends.

### 🔍Process
##### 1. Data Exploration
- Reviewed all tables (Customers, Orders, Order Details, Products, etc.)
- Identified data quality issues and defined key business questions like:
    - Who are our top customers?
    - Which products drive the most revenue?

##### 2. Data Cleaning & Preparation
- Removed duplicates and handled missing values
- Created calculated fields (e.g., Total Sales = Unit Price × Quantity × (1 - Discount))
- Standardized date formats and discount values
- Extracted key time fields for trend analysis:
    - Order Month & Day
    - Shipping Month & Day
    - Delivery Time in Days
    - Required Shipping Time
    - Delay or Early Delivery Indicator
    - Created a “Shipping Status” helper column to flag incomplete orders (missing shipping dates)
    - Converted raw data to Excel Tables for easier referencing and interaction

##### 3. Data Modeling
- Built relationships between fact tables (Orders, Order Details) and dimension tables (Customers, Products, Employees) using the Excel Data Model

### 📈 KPI Development & Analysis
I grouped the KPIs by business function and used PivotTables to develop the analysis:
- Sales Performance
    - Total Revenue
    - Total Orders
    - Average Order Value (AOV)
    - Sales by Product Category
    - Top-Selling Products
    - Revenue by Country

- Customer Insights
    - Total Customers
    - Repeat Customers
    - Top 10 Customers by Revenue
    - Customer Lifetime Value (CLV) Estimate

- Employee Performance
    - Orders Handled per Employee
    - Revenue per Employee
    - Average Order Value per Employee

- Shipping & Fulfillment
    - Average Shipping Time
    - Orders per Shipper
    - Average Shipping Cost per Shipper

 ### 📊 Dashboard Features
The final dashboard includes a mix of:
- Line, bar, column, and pie charts
- Timeline filters and slicers for:
    - Product Category
    - Time Period
    - Customer
    - Employee

The dashboard is fully interactive, allowing stakeholders to explore and drill down into various dimensions of the business.
