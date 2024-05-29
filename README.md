# Exploring_Crypto_Market

This project analyzes cryptocurrency market data to visualize market capitalization and volatility. The data is sourced from CoinMarketCap and processed using pandas and Matplotlib for visualization.

## Overview
The goal of this project is to:

1. Visualize the top 10 cryptocurrencies by market capitalization.
2. Analyze the volatility of cryptocurrencies over 24-hour and 7-day intervals.
3. Categorize cryptocurrencies based on their market capitalization.

## Steps
1. Data Loading and Preprocessing:
- Load the dataset using pandas.
- Filter out rows without market capitalization data.

2. Market Capitalization Analysis:
- Select the top 10 cryptocurrencies by market capitalization.
- Calculate the market capitalization percentage for each cryptocurrency.
- Plot the market capitalization data.

3. Volatility Analysis:
- Analyze the percentage change in cryptocurrency prices over 24-hour and 7-day intervals.
- Plot the top 10 winners and losers for both time periods.

4. Categorize Cryptocurrencies:
- Categorize cryptocurrencies into different market cap sizes (large, mid, small).
- Count the number of cryptocurrencies in each category.
- Plot the counts of cryptocurrencies per size category.
