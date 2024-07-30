# FAANG Stock Data Analysis

This project analyzes the stock performance of five major technology companies: Facebook, Amazon, Apple, Netflix, and Google (FAANG). The analysis includes historical stock prices and daily returns.

## Dataset

The dataset includes historical stock prices and volumes for the following companies:
- Facebook (FB)
- Amazon (AMZN)
- Apple (AAPL)
- Netflix (NFLX)
- Google (GOOGL)

## Visualizations

### 1. FAANG Companies Closing Prices Over Time

![Closing Prices Over Time](https://github.com/tnaiboa/faang-stock-data-analysis/raw/main/images/ClosingPrices.png)

### 2. Companies Daily Return Over Time

![Daily Return Over Time](https://github.com/tnaiboa/faang-stock-data-analysis/raw/main/images/DailyReturns.png)

### Dashboard

You can interact with the full dashboard on [Tableau Public](https://public.tableau.com/views/FAANGStockAnalysisDashboard/FAANGStockAnalysisDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## Analysis Overview

### Data Loading and Preparation

The data for each company is loaded from CSV files, combined into a single DataFrame, and prepared for analysis.

### Daily Returns

We calculate the daily returns for each company to understand the day-to-day changes in stock prices.

### Volatility

Volatility is calculated as the rolling standard deviation of daily returns over a 30-day window, indicating the degree of variation in stock prices.

### Correlation Analysis

We analyze the correlation between the daily returns of the FAANG companies to understand how their stock prices move in relation to each other.

## Visualizations

The analysis includes various plots to visualize the closing prices, daily returns, volatility, and correlations.

## License

This project is licensed under the MIT License.
