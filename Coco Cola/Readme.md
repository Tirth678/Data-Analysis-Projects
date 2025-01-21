<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coca-Cola Stock Analysis</title>
</head>
<body>
    <header>
        <h1>Coca-Cola Stock Analysis</h1>
    </header>

    <section id="overview">
        <h2>Overview</h2>
        <p>This project aims to analyze historical Coca-Cola stock data to uncover trends, patterns, and insights into stock price behavior and trading volume. Through data cleaning, feature engineering, and visualizations, the project provides a comprehensive understanding of Coca-Cola's stock performance.</p>
    </section>

    <section id="dataset-details">
        <h2>Dataset Details</h2>
        <ul>
            <li><strong>Source:</strong> <a href="https://drive.google.com/drive/folders/19oBqp11Af9MDTz8ODGcmv7_Nj_L9tLNp?usp=sharing" target="_blank">Coca-Cola Stock Data</a></li>
            <li><strong>Columns:</strong>
                <ul>
                    <li><code>Date</code>: Trading date.</li>
                    <li><code>Open</code>: Opening price of the stock.</li>
                    <li><code>High</code>: Highest price of the day.</li>
                    <li><code>Low</code>: Lowest price of the day.</li>
                    <li><code>Close</code>: Closing price of the stock.</li>
                    <li><code>Volume</code>: Number of shares traded.</li>
                    <li><code>Dividends</code>: Dividends paid on the day.</li>
                    <li><code>Stock Splits</code>: Stock split ratio.</li>
                </ul>
            </li>
        </ul>
    </section>

    <section id="tools-technologies">
        <h2>Tools and Technologies Used</h2>
        <ul>
            <li><strong>Programming Language:</strong> Python</li>
            <li><strong>Libraries:</strong>
                <ul>
                    <li><code>pandas</code>: For data manipulation.</li>
                    <li><code>matplotlib</code> and <code>seaborn</code>: For data visualization.</li>
                </ul>
            </li>
            <li><strong>Environment:</strong> Jupyter Notebook</li>
        </ul>
    </section>

    <section id="workflow">
        <h2>Project Workflow</h2>

        <h3>1. Data Preparation</h3>
        <ul>
            <li><strong>Loading Data:</strong> Loaded Coca-Cola stock data either from a CSV file or via Yahoo Finance API.</li>
            <li><strong>Data Cleaning:</strong>
                <ul>
                    <li>Filled missing values using forward fill for continuity.</li>
                    <li>Verified and corrected data types.</li>
                </ul>
            </li>
        </ul>

        <h3>2. Feature Engineering</h3>
        <ul>
            <li>Calculated 20-day and 50-day moving averages to identify trends.</li>
            <li>Computed percentage changes in daily closing prices to measure performance.</li>
            <li>Calculated rolling standard deviation of daily returns to analyze stock volatility.</li>
        </ul>

        <h3>3. Exploratory Data Analysis (EDA)</h3>
        <ul>
            <li><strong>Summary Statistics:</strong> Described key metrics such as mean, standard deviation, and range for all numerical columns.</li>
            <li><strong>Visualizations:</strong>
                <ul>
                    <li><strong>Line Charts:</strong> Displayed stock prices over time with moving averages.</li>
                    <li><strong>Bar Charts:</strong> Showed monthly trading volumes.</li>
                    <li><strong>Heatmaps:</strong> Illustrated correlations among stock attributes.</li>
                    <li><strong>Volatility Trends:</strong> Highlighted changes in stock price stability over time.</li>
                </ul>
            </li>
        </ul>
    </section>

    <section id="insights">
        <h2>Key Insights</h2>
        <ol>
            <li><strong>Stock Price Trends:</strong> Identified significant upward trends using moving averages.</li>
            <li><strong>Trading Volume Patterns:</strong> Monthly trading volume analysis revealed periods of increased market activity.</li>
            <li><strong>Volatility Observations:</strong> Highlighted periods of high and low market stability.</li>
            <li><strong>Correlation Analysis:</strong> Found strong relationships between attributes such as opening and closing prices.</li>
        </ol>
    </section>

    <section id="usage">
        <h2>How to Use This Project</h2>
        <ol>
            <li><strong>Clone Repository:</strong> Download or clone the project files from the provided source link.</li>
            <li><strong>Install Dependencies:</strong> Ensure required Python libraries are installed:
                <pre><code>pip install pandas matplotlib seaborn yfinance</code></pre>
            </li>
            <li><strong>Run the Code:</strong> Execute the Jupyter Notebook to generate insights and visualizations.</li>
        </ol>
    </section>

    <section id="future-work">
        <h2>Future Enhancements</h2>
        <ul>
            <li>Compare Coca-Cola’s stock performance with competitors in the same industry.</li>
            <li>Integrate macroeconomic indicators (e.g., inflation, GDP) to analyze their impact on stock performance.</li>
            <li>Develop an interactive dashboard for real-time analysis.</li>
        </ul>
    </section>

    <section id="acknowledgments">
        <h2>Acknowledgments</h2>
        <ul>
            <li><strong>Dataset:</strong> Courtesy of Yahoo Finance and public repositories.</li>
            <li><strong>Inspiration:</strong> Based on open-source data analysis projects.</li>
        </ul>
    </section>

</body>
</html>

