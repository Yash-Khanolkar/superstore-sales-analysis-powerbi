# superstore-sales-analysis-powerbi
Power BI Sales Performance Dashboard analyzing profit, sales trends, customer behavior, and regional performance using Superstore dataset.

Project Title
Superstore Sales Analysis & Executive Dashboard | Power BI

Headline
End-to-end sales data analysis project featuring KPI tracking, profitability analysis, customer insights, and executive-level visualization design.

Project Overview
This project presents an interactive Sales Performance Dashboard developed using Power BI and SQL to analyze business performance across sales, profit, customer segments, and regional markets.
The objective of this project was to transform raw transactional data into actionable business insights through data cleaning, transformation, modeling, and visualization.
The dashboard enables decision-makers to monitor KPIs, identify growth opportunities, and evaluate profitability drivers.

Business Objectives
Track overall Sales, Profit, and Profit Margin performance

Identify top-performing customer segments

Analyze regional contribution to revenue and profit

Evaluate shipping mode impact on profitability

Detect seasonal sales trends

Identify Top 5 Customers by Sales contribution

Compare profitability across product categories

Key KPIs & Metrics
Total Sales: 2.27M
Total Profit: 282.86K
Profit Margin: 12.45%
Total Orders: 5K
Custom DAX Measures Created:
Total Sales = SUM(Sales)
Total Profit = SUM(Profit)
Profit Margin = DIVIDE([Total Profit], [Total Sales])

Dashboard Insights
Segment Analysis
Consumer segment contributes ~47% of total profit
Corporate segment is second highest contributor
Home Office generates comparatively lower profit

Regional Performance
West region generates highest profit
Central region underperforms relative to other regions

Category Profitability
Technology is the most profitable category
Furniture shows lowest profit margin, indicating potential pricing or cost challenges

Shipping Mode Impact
Standard Class contributes the highest sales and profit
Premium shipping modes contribute less revenue proportionally

Seasonal Trends
Sales peak during Q4 (October–December)
Indicates strong seasonal demand and inventory planning importance

Customer Contribution
Top 5 customers significantly impact overall revenue
Suggests opportunity for customer retention and loyalty strategies

Data Preparation Process
Extracted and explored dataset using SQL
Imported data into Power BI
Cleaned and transformed data (corrected date formats, data types, sorting logic)
Built calculated columns and DAX measures
Designed executive-level dashboard layout with structured visual storytelling

Repository Contents
Retail Sales Report.pbix – Power BI dashboard file
Superstore_Raw_Data.xlsx – Raw dataset used for analysis
Sales Report Dashboard.png – Dashboard snapshot
README.md – Project documentation

Business Value
This dashboard provides a centralized performance view enabling:
Strategic sales planning
Profitability optimization
Regional performance evaluation
Customer-focused revenue strategy
Executive-level reporting

Data Source
The dataset used for this project is the Superstore Sales Dataset sourced from Kaggle.

Screenshot/ Uploads
Dashboard Snapshot: ![Dashboard Preview](https://github.com/Yash-Khanolkar/superstore-sales-analysis-powerbi/blob/main/Sales%20Report%20Dashboard.png)
