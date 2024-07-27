# faang-stock-data-analysis
SQL projects analyzing FAANG stock data
# FAANG Stock Data Analysis

This repository contains SQL scripts and Jupyter Notebooks for analyzing the FAANG stock data.

## Dataset

The dataset includes historical stock prices and volumes for the following companies:
- Facebook (FB)
- Amazon (AMZN)
- Apple (AAPL)
- Netflix (NFLX)
- Google (GOOGL)

## Project Structure

- `sql/`: Contains SQL scripts for creating tables and performing queries.
- `notebooks/`: Contains Jupyter Notebooks for data visualization.
- `data/`: Contains the dataset (not included in the repository, download from Kaggle).

## Getting Started

1. Set up a PostgreSQL or MySQL database.
2. Import the dataset into the database using the provided SQL scripts.
3. Run the SQL scripts in the `sql/` directory.
4. Use the Jupyter Notebooks in the `notebooks/` directory to visualize the results.

## Queries

- Calculate average closing price by company.
- Find the highest closing price for each company.
- Calculate the average daily volume for each company.
- Find the date with the highest trading volume for each company.
- Calculate monthly average closing prices.
- Calculate moving averages (50-day and 200-day).
- Identify crossover points between short-term and long-term moving averages (Golden Cross and Death Cross).

## Visualization

Use the Jupyter Notebooks to create visualizations for the queries. The notebooks demonstrate how to plot closing prices, moving averages, and identify crossover points.

## License

This project is licensed under the MIT License.
