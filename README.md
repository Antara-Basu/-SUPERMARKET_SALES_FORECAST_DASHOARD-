# -SUPERSTORE_SALES_FORECAST_DASHOARD-

# Objective:
To contribute to the success of business by utilizing data analysis techniques specifically  focusing on time series analysis to provide valuable insights and accurate sales forecasting.
# The objective can be detailed
# 1.) Dashboard Creation: 
Identify the KPIs, design an
Intuitive & visually appealing dashboard, add
interactive
visualizations and filtering capabilities 
to allow users to explore the data at various levels of granularity.
# 2) Data Analysis : 
Provide valuable insights to business entities regarding the effectiveness of their sales strategies thr
visualizations & charts.
# 3) Sales Forecasting:
Leverate historical data & time series analysis to generate sales forecasts 
for the next  15 days
# 4) Actionable for Insights & Recommendations:
The end goal is to shore valuable insights & actionable information that can drive strategic
decisions. Support the supermarket's goals and growth efficiency.

# Import and Data Cleaning
Searched null values, deleted duplicates, replaced values in all columns, and removed empty columns.


# Project Insights
1) The max payment or sales is coming from COD. So cards have less sales . Then to increase 
see which cards are there if credit cards, give an offer to the company
of the credit card.
3)Max sales are in West Region, 33%, and California is contributing the most.
4)They give delivery in 4 days.











DAX QUERY
AvgDelivery = DATEDIFF('Superstore_Sales_Dataset'[Order Date],'Superstore_Sales_Dataset'[Ship Date],Day)

Did Sales Forecasting for the next 15 days, 1st January to  14th January.
