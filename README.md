# Sales Analysis and Forecasting Dashboard

# Project Overview
This project involves creating a comprehensive Power BI dashboard to analyze sales data, forecast future trends, and support strategic business decisions.

# Key Components

# 1. Dashboard Creation
- **Identify KPIs**: Total profit, total sales, total quantity, total orders, and average shipping days.
- **Design**: Create an intuitive and visually appealing dashboard layout.
- **Interactivity**: Add interactive visualizations and filtering capabilities for detailed data exploration.

# 2. Data Analysis
- **Insight Generation**: Utilize visualizations and charts to uncover valuable insights into sales strategies.
- **Trend Analysis**: Analyze temporal trends with stacked area charts to observe sales patterns for 2019 and 2020.

# 3. Sales Forecasting
- **Time Series Analysis**: Use historical data to generate sales forecasts for the next 15 days.

# 4. Actionable Insights & Recommendations
- **Strategic Decision Support**: Provide actionable insights to drive strategic business decisions.
- **Business Growth**: Support the supermarket’s goals and enhance operational efficiency.

# Data Preparation
- **Import and Clean Data**: Address missing values, remove duplicates, replace incorrect values, and eliminate empty columns to ensure high-quality data.

## Project Insights

# KPI Highlights
- **Total Profit**: Overall profitability measurement.
- **Total Sales**: Total revenue generated from sales.
- **Total Quantity**: Number of items sold.
- **Total Orders**: Count of orders placed.
- **Average Shipping Days**: Average time taken for order shipment.

## DAX Query Example
To calculate the average delivery time, the following DAX query was used:
DAX
AvgDelivery = DATEDIFF('Superstore_Sales_Dataset'[Order Date],'Superstore_Sales_Dataset'[Ship Date],Day)

# Temporal Sales Trends
- **Sales by Order Date (2019-2020)**: Stacked area chart reveals highest sales in December and significant sales increase between October and March.
- **Monthly Profit YoY (2019-2020)**: Stacked area chart shows peak profit in December 2019, reaching 17K.

# Category and Customer Insights
- **Quantity by Subcategory**: Clustered column chart shows highest sales in binders with 3.7K units.
- **Top 10 Customers by Profit**: Stacked column chart highlights the most profitable customers.

# Product Performance
- **Top 5 Products by Sales**: Clustered bar chart identifies best-selling products.
- **Bottom 5 Products by Sales**: Clustered bar chart shows least-selling products for further analysis and improvement.

# Regional Analysis
- **Region Filters**: Analyze sales performance across Central, South, East, and West regions using interactive filters.

# Conclusion and Recommendations
- **Identify Peak Sales Periods**: Strategize marketing efforts based on peak sales times.
- **Improve Underperforming Products**: Focus on enhancing sales for products with low performance.
- **Customer Retention Strategies**: Develop strategies to retain top customers and boost profitability.
- **Optimize Regional Strategies**: Tailor business strategies to regional performance.


This Power BI dashboard is a powerful tool for sales data analysis and trend identification. Users can interact with various visualizations and filters to derive meaningful insights and drive business growth.

Collectively, these insights not only provide a comprehensive picture of sales trends but also furnish actionable information for strategic decision-making. By leveraging these findings, stakeholders can tailor their strategies, optimize operations, and enhance customer engagement to ensure sustained growth and success in the competitive marketplace.
