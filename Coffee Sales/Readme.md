<h1>Coffee Sales Analysis Project</h1> <br>
<h2>Overview</h2> <br>
This project analyzes coffee sales data from a vending machine to uncover trends, patterns, and customer preferences. The analysis includes detailed exploratory data analysis (EDA) to identify purchasing behaviors, sales trends, and peak transaction times. These insights can aid inventory management, product optimization, and decision-making.

Dataset Details
Source: The dataset is publicly available and can be downloaded from this link.
Data Collection Period: March 2024 to present.
Columns:
date: Transaction date.
datetime: Exact transaction timestamp.
cash_type: Payment type (Cash or Card).
card: Identifier for card users.
money: Transaction amount.
coffee_name: Name of the purchased coffee.
Tools Used
Python Libraries:
pandas: Data manipulation.
matplotlib and seaborn: Data visualization.
Environment: Jupyter Notebook.
Key Steps in Analysis
1. Data Preparation
Converted date and datetime columns to datetime format.
Extracted additional features: month, day (weekday), and hour (time of day).
Handled missing values in the card column by identifying cash transactions.
2. Exploratory Data Analysis (EDA)
Coffee Type Analysis
Identified the most and least popular coffee types.
Top Sellers: Americano with Milk, Latte.
Low Sellers: Cocoa, Espresso.
Payment Method Analysis
Analyzed transaction distribution between cash and card users.
Key Insight: 92% of transactions were made using cards.
Temporal Analysis
Daily Patterns:
Sales peaked on Tuesdays.
Hourly Trends:
Two daily peaks observed: 10:00 AM and 7:00 PM.
Products like Latte were most popular in the morning, while Cappuccino and Hot Chocolate were preferred in the evening.
Revenue Trends
Calculated total revenue contributions by coffee type.
Highest Revenue Contributor: Latte.
3. Visualizations
Bar Charts:
Coffee type sales.
Revenue by coffee type.
Transactions by payment type.
Line Charts:
Monthly sales trends for different coffee types.
Hourly sales trends across coffee types.
Heatmaps:
Sales by hour and weekday.
Insights and Conclusions
Americano with Milk and Latte are the most popular coffee types, with Latte generating the highest revenue.
Card transactions dominate, indicating a preference for cashless payments.
Peak sales times and days can inform optimal restocking schedules and promotional campaigns.
Seasonal trends show opportunities for product-specific marketing.
Future Work
Further segmentation of customer preferences.
Identifying cross-selling opportunities (e.g., pairing coffee types).
Advanced dashboard creation for interactive reporting.
Acknowledgments
Dataset provided by Yaroslav Isaienkov (@ihelon) on Kaggle.
Inspired by sample projects for data analytics guidance.
