<h1>Coca-Cola Stock Analysis</h1>
<br>
<h2>Overview</h2>
<br> <br>

This project aims to analyze historical Coca-Cola stock data to uncover trends, patterns, and insights into stock price behavior and trading volume. Through data cleaning, feature engineering, and visualizations, the project provides a comprehensive understanding of Coca-Cola's stock performance.

Dataset Details

Source: Coca-Cola Stock Data

Columns:

Date: Trading date.

Open: Opening price of the stock.

High: Highest price of the day.

Low: Lowest price of the day.

Close: Closing price of the stock.

Volume: Number of shares traded.

Dividends: Dividends paid on the day.

Stock Splits: Stock split ratio.

Tools and Technologies Used

Programming Language: Python

Libraries:

pandas: For data manipulation.

matplotlib and seaborn: For data visualization.

Environment: Jupyter Notebook

Project Workflow

1. Data Preparation

Loading Data: Loaded Coca-Cola stock data either from a CSV file or via Yahoo Finance API.

Data Cleaning:

Filled missing values using forward fill for continuity.

Verified and corrected data types.

2. Feature Engineering

Moving Averages: Calculated 20-day and 50-day moving averages to identify trends.

Daily Returns: Computed percentage changes in daily closing prices to measure performance.

Volatility: Calculated rolling standard deviation of daily returns to analyze stock volatility.

3. Exploratory Data Analysis (EDA)

Summary Statistics:

Described key metrics such as mean, standard deviation, and range for all numerical columns.

Visualizations:

Line Charts: Displayed stock prices over time with moving averages.

Bar Charts: Showed monthly trading volumes.

Heatmaps: Illustrated correlations among stock attributes.

Volatility Trends: Highlighted changes in stock price stability over time.

Key Insights

Stock Price Trends:

Identified significant upward trends using moving averages.

Trading Volume Patterns:

Monthly trading volume analysis revealed periods of increased market activity.

Volatility Observations:

Highlighted periods of high and low market stability.

Correlation Analysis:

Found strong relationships between attributes such as opening and closing prices.

How to Use This Project

Clone Repository:
Download or clone the project files from the provided source link.

Install Dependencies:
Ensure required Python libraries are installed:

pip install pandas matplotlib seaborn yfinance

Run the Code:
Execute the Jupyter Notebook to generate insights and visualizations.

Future Enhancements

Compare Coca-Cola’s stock performance with competitors in the same industry.

Integrate macroeconomic indicators (e.g., inflation, GDP) to analyze their impact on stock performance.

Develop an interactive dashboard for real-time analysis.

Acknowledgments

Dataset: Courtesy of Yahoo Finance and public repositories.

Inspiration: Based on open-source data analysis projects.

This project provides a solid foundation for understanding stock performance and serves as a useful tool for both investors and analysts.

