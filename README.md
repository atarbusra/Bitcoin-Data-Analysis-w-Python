# Bitcoin-Data-Analysis-w-Python

## Overview
This project focuses on analyzing Bitcoin price data over time, utilizing Python for data cleaning, preparation, and visualization. The goal is to uncover trends, patterns, and key insights from historical Bitcoin prices through various analyses such as daily price changes, volatility, and candlestick chart visualizations.

## Dataset
The dataset contains historical Bitcoin price data with the following fields:

Date: The date of the price record.

Open: Opening price of Bitcoin for the day.

High: Highest price of Bitcoin for the day.

Low: Lowest price of Bitcoin for the day.

Close: Closing price of Bitcoin for the day.

Volume: Trading volume of Bitcoin.

Market Cap: Market capitalization of Bitcoin.

## Key Analyses
### Data Preprocessing:
Converted the Date column into a datetime format.
Handled missing values and ensured correct data types for analysis.

### OHLC (Open, High, Low, Close) Analysis:
Visualized the price trends over time using candlestick charts.
Analyzed price volatility through the differences between opening, closing, high, and low prices.

### Daily Price Changes:
Computed daily changes in Bitcoin’s closing price to understand volatility.
Investigated significant fluctuations and trends over time.

### Time Series Visualization:
Visualized key metrics like closing prices and volume over various time periods (daily, monthly, yearly).
Highlighted periods of high and low volatility in Bitcoin trading.

### Libraries Used
The project makes use of the following Python libraries:
Pandas: For data manipulation, cleaning, and organizing time series data.
NumPy: For numerical operations and array manipulations.
Matplotlib: For static visualizations of the time series data.
Seaborn: For enhanced data visualizations and styling.
Plotly: Used for creating interactive visualizations, including candlestick charts.


## Results
OHLC Analysis: Insights into the trends of Bitcoin prices over time.
Volatility Study: Daily fluctuations in the Bitcoin market.
Visualizations: Candlestick charts and line graphs to represent Bitcoin price movements.
