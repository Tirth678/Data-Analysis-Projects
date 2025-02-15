# Coca-Cola Stock Analysis

## Overview
This project focuses on analyzing historical Coca-Cola stock data to identify trends, patterns, and insights related to stock price behavior and trading volume. The analysis includes various visualizations and statistical metrics to understand the stock's performance over time.

## Key Objectives
- Analyze stock price trends using moving averages.
- Examine trading volume patterns.
- Investigate volatility and its impact on stock performance.
- Explore correlations between different stock metrics.
- Compare trading behavior on weekdays vs weekends.

## Data Sources
The data used in this analysis is obtained from Yahoo Finance using the `yfinance` library. It includes historical stock data for Coca-Cola (ticker: KO) from January 1, 2015, to December 31, 2023.

## Analysis Steps
1. **Data Collection**: Fetch historical stock data using `yfinance`.
2. **Data Cleaning**: Handle missing values and ensure data consistency.
3. **Feature Engineering**: Calculate moving averages, daily returns, and volatility.
4. **Exploratory Data Analysis**: Perform initial data exploration to understand the dataset.
5. **Visualization**: Create various plots to visualize trends and patterns.
6. **Behavioral Analysis**: Analyze trading volume and behavior over time.

## Visualizations Included
- Stock prices with 20-day and 50-day moving averages.
- Correlation heatmap of stock metrics.
- Volatility trends over time.
- Monthly trading volume analysis.
- Weekend vs weekday trading volume comparison.

## Usage Instructions
1. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy seaborn matplotlib yfinance
   ```
2. Open the `Notebook.ipynb` file in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to execute the analysis.
4. The cleaned dataset is saved as `cleaned_coca_cola_stock.csv` for further use.

## Dependencies
- Python 3.7+
- pandas
- numpy
- seaborn
- matplotlib
- yfinance

## License
This project is licensed under the MIT License. See the LICENSE file for details.
