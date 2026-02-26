# Ecommerce-Sales-Dashboard-using-Power-BI
The Ecommerce Sales Dashboard using Power BI project is an end-to-end business intelligence solution designed to analyze ecommerce sales performance, customer behavior, and product trends.
This dashboard helps stakeholders monitor KPIs, identify sales patterns, track profitability, and make data-driven decisions.

🎯 Project Objective

Analyze ecommerce sales data

Track revenue, profit, and order performance

Identify top-performing products and categories

Understand customer purchasing behavior

Monitor regional sales distribution

Provide interactive insights through dynamic visualizations

🛠️ Tools & Technologies Used

Microsoft Power BI

Power Query (Data Transformation)

DAX (Data Analysis Expressions)

Excel / CSV Dataset

📂 Dataset Description

The dataset contains the following columns:

Order ID

Order Date

Customer Name

State

City

Region

Product Category

Sub-Category

Product Name

Sales

Quantity

Discount

Profit

📊 Dashboard Features
📄 Page 1: Sales Overview

KPIs:

Total Sales

Total Profit

Total Orders

Profit Margin %

Visuals:

Sales Trend (Line Chart)

Sales by Category (Bar Chart)

Sales by Region (Map / Filled Map)

Monthly Sales Analysis

Top 10 Products by Sales

Slicers:

Date

Region

Category

📄 Page 2: Customer & Regional Analysis

KPIs:

Total Customers

Repeat Customers

Average Order Value

Total Quantity Sold

Visuals:

Sales by State

Customer Distribution

Region-wise Profit

Top Customers by Revenue

Quantity by Category

Slicers:

Region

State

Date

📄 Page 3: Profitability & Product Analysis

KPIs:

Total Discount

Average Discount %

Loss-Making Products

Highest Profit Product

Visuals:

Profit by Sub-Category

Discount vs Profit Scatter Plot

Bottom 10 Products by Profit

Category-wise Profit Contribution

Profit Trend Over Time

Slicers:

Category

Sub-Category

Date

🔄 Data Transformation Steps (Power Query)

Removed null values

Corrected data types

Created Date hierarchy (Year, Month)

Created calculated columns:

Profit Margin %

Year-Month

Removed duplicates

Handled outliers (if any)

📐 Data Modeling

Star Schema Model

Fact Table: Sales Data

Dimension Tables:

Date Table

Product Table

Customer Table

Region Table

Relationships built using primary and foreign keys.

🧮 Important DAX Measures
Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Orders = DISTINCTCOUNT(Sales[Order ID])

Profit Margin % = 
DIVIDE([Total Profit], [Total Sales], 0)

Average Order Value = 
DIVIDE([Total Sales], [Total Orders], 0)
📈 Business Insights Generated

Identified high-revenue categories

Detected loss-making sub-categories

Analyzed seasonal sales trends

Evaluated impact of discounts on profitability

Discovered top-performing regions and customers

🚀 How to Use This Project

Download the .pbix file from this repository

Open using Microsoft Power BI Desktop

Refresh dataset (if connected to external source)

Interact with slicers and visuals to explore insights

📷 Dashboard Preview

(Add dashboard screenshots here)

📌 Key Learnings

Data cleaning using Power Query

Building interactive dashboards

Writing optimized DAX measures

Designing business-focused KPIs

Creating professional BI reports

📎 Project File

Ecommerce_Sales_Dashboard.pbix

👨‍💻 Author

Sujal Dhanwij
Aspiring Data Analyst
Skilled in Power BI | Excel | Python | SQL
