# 📈 TCS Stock Market Analysis Using Python

A beginner-friendly data analysis project that explores historical stock price movements of Tata Consultancy Services (TCS) using Python, Pandas, NumPy, and Plotly.

## 📌 Project Overview

This project analyzes historical TCS stock market data to understand price movements, daily returns, moving averages, and volatility. It demonstrates how Python can be used to collect, process, analyze, and visualize financial data.

The analysis is performed in a Google Colab notebook, making the project easy to run and reproduce.

## 🎯 Objectives

- Retrieve historical TCS stock data using Python.
- Visualize historical closing prices.
- Analyze short-term price trends using moving averages.
- Calculate overall percentage price change.
- Calculate daily percentage returns.
- Identify the highest and lowest closing prices.
- Measure daily return volatility.
- Summarize key findings using numerical analysis.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming and analysis |
| Google Colab | Cloud-based notebook environment |
| yfinance | Retrieving historical stock data |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical calculations and statistics |
| Plotly | Interactive data visualizations |

## 📊 Features

### 1. Historical Stock Price Visualization
An interactive line chart displays TCS closing prices over the selected period.

### 2. Moving Average Analysis
20-day and 30-day moving averages help visualize underlying price trends and reduce the impact of short-term fluctuations.

### 3. Closing Price Analysis
Calculates the first and last available closing prices, overall percentage price change, and highest and lowest closing prices during the selected period.

### 4. Daily Returns Analysis
Calculates daily percentage returns to examine price changes between consecutive available observations.

### 5. Volatility Analysis
Uses the standard deviation of daily percentage returns to measure how much daily returns fluctuate over the selected period.

### 6. Automatic Analysis Summary
Displays key numerical results and a simple interpretation of the observed price movement.

## 📚 Key Concepts Learned

- Working with financial time-series data
- Handling missing values
- Data cleaning and preprocessing
- Percentage change calculations
- Moving averages
- Mean and standard deviation
- Interactive data visualization
- Writing and organizing Python notebooks

## 🚀 How to Run the Project

1. Open the notebook in Google Colab.
2. Install any required libraries if they are not already available:

   ```python
   !pip install yfinance pandas numpy plotly
   ```

3. Run the notebook cells from top to bottom.
4. Explore the charts and review the calculated statistics.

**Note:** The project retrieves historical data through Yahoo Finance using `yfinance`, so an internet connection is required to download fresh data.

## 📁 Project Structure

```text
tcs-stock-analysis/
├── README.md
└── tcs_stock_analysis.ipynb
```

## 🔍 Results and Findings

The notebook calculates and displays:

- Overall closing-price percentage change
- Highest and lowest closing prices
- Average daily return
- Daily return volatility
- Historical price charts and moving averages

The numerical findings depend on the selected date range and the data retrieved when the notebook is executed.

## ⚠️ Disclaimer

This project is intended for educational purposes only. It analyzes historical stock price data and does not provide financial advice, investment recommendations, or predictions of future stock performance.

## 👨‍💻 Author

Created as a beginner Python data analysis project to develop practical skills in programming, numerical analysis, and data visualization.
