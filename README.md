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

In this comprehensive analysis, we have embarked on a data-driven exploration of sales trends and patterns within the dataset. The utilization of various visualization techniques has empowered us to extract meaningful insights that provide a deeper understanding of the dynamics at play.

Through the clustered bar charts, we have identified pivotal categories, sub-categories, and ship modes that significantly contribute to cumulative sales. Notably, 'Office Supplies,' 'Technology,' and 'Furniture' stand out as the top three categories driving sales, while 'Phones,' 'Chairs,' 'Binders,' and 'Storage' emerge as the primary sub-categories influencing sales figures. Additionally, the ship modes 'Standard Class,' 'Second Class,' 'First Class,' and 'Same Class' play a crucial role in shaping sales distribution.

Turning our attention to the temporal aspect, the stacked area chart unveils intriguing trends in sales categorized by order date for 2019 and 2020. This visualization reveals that December holds the highest sales, with a noticeable surge in sales between 2019 and 2020, particularly evident in the months of October and March.

Geographical insights come to the fore with a map visualization displaying the distribution of sales across different states. The visualization, utilizing bubbles, highlights California as the leading state in terms of sales, indicating its prominent contribution to the overall sales landscape.

Furthermore, the donut charts provide a deeper understanding of the distribution of segments and payment modes. The revelation that Consumer segment sales account for 48%, followed by Corporate at 33%, and Home Office at 19%, highlights the diversity in customer groups and their respective contributions. Meanwhile, the distribution of payment modes underscores the prevalence of Cash on Delivery (COD) at 43%, Online payments at 35%, and Card payments at 22%, emphasizing the significance of COD as the predominant payment method.So cards have less sales . Then to increase 
see which cards are there if credit cards, give an offer to the company
of the credit card.
Also, They give average delivery in 4 days.

Lastly, our examination of the top 10 ship states influencing superstore sales underscores the crucial role played by states such as California, New York, Texas, and others. These states collectively represent the driving force behind the majority of sales.

Collectively, these insights not only provide a comprehensive picture of sales trends but also furnish actionable information for strategic decision-making. By leveraging these findings, stakeholders can tailor their strategies, optimize operations, and enhance customer engagement to ensure sustained growth and success in the competitive marketplace.


DAX QUERY
AvgDelivery = DATEDIFF('Superstore_Sales_Dataset'[Order Date],'Superstore_Sales_Dataset'[Ship Date],Day)

Did Sales Forecasting for the next 15 days, 1st January to  14th January.
