Coca-Cola Stock Analysis

Overview

This project focuses on analyzing historical Coca-Cola stock data to identify trends, patterns, and insights related to stock price behavior and trading volume. By applying data cleaning, feature engineering, and visualization techniques, it provides a comprehensive understanding of the stock's performance over time.

Dataset Details

Source: Coca-Cola Stock Data

Columns:

Date: Trading date.

Open: Opening price of the stock.

High: Highest price during the day.

Low: Lowest price during the day.

Close: Closing price of the stock.

Volume: Number of shares traded.

Dividends: Dividends paid on the day.

Stock Splits: Stock split ratio.

Tools and Technologies Used

Programming Language: Python

Libraries:

pandas: Data manipulation and cleaning.

matplotlib and seaborn: Data visualization.

Environment: Jupyter Notebook

Project Workflow

Data Preparation

Loaded Coca-Cola stock data from a CSV file or Yahoo Finance API.

Cleaned data by:

Filling missing values using forward fill.

Ensuring data types were consistent.

Feature Engineering

Calculated moving averages (20-day and 50-day) to identify trends.

Computed daily percentage changes to measure performance.

Measured rolling standard deviations to analyze stock volatility.

Exploratory Data Analysis (EDA)

Summary Statistics: Generated key metrics like mean, standard deviation, and range.

Visualizations:

Line charts showing stock prices and moving averages over time.

Bar charts analyzing monthly trading volumes.

Heatmaps illustrating correlations among stock attributes.

Volatility trends highlighting periods of stability and instability.

Key Insights

Stock Price Trends: Moving averages revealed consistent upward trends over long periods.

Trading Volume: Monthly analysis indicated spikes during significant market events.

Volatility: Certain periods showed increased volatility, often correlating with major news or events.

Correlations: Strong relationships observed between opening and closing prices.

How to Use This Project

Clone Repository: Download the project files from the source link.

Install Dependencies: Run the following command to install required libraries:

pip install pandas matplotlib seaborn yfinance

Execute the Notebook: Open the Jupyter Notebook and run the cells to reproduce the analysis and visualizations.

Future Enhancements

Expand the analysis to compare Coca-Cola's stock with competitors in the beverage industry.

Incorporate macroeconomic indicators (e.g., inflation rates, GDP growth) to understand their impact on stock performance.

Build an interactive dashboard for dynamic, real-time analysis.

Acknowledgments

Dataset: Provided via Yahoo Finance and public data repositories.

Inspiration: Adapted from open-source stock analysis projects and resources.

This project serves as a foundation for further analysis and offers valuable insights for investors and analysts interested in Coca-Cola's stock performance.

