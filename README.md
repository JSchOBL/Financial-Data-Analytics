# Financial-Data-Analytics

## Project Goal

This project analyzes financial market data to compare U.S. NASDAQ stocks and cryptocurrencies, assess data quality, evaluate risk-return behavior, and explore basic portfolio and forecasting strategies.

## What Was Analyzed

- Stock data from NASDAQ-listed companies, including weekly aggregated returns, share performance, and sector composition.
- Cryptocurrency data, with a focus on weekly returns, market breadth, and volatility patterns.
- Metadata such as ticker, sector, IPO year, and company details to support sector, lifetime, and quality analysis.
- Portfolio concepts including savings-plan scenarios, Sharpe ratio comparisons, and correlation between major stocks and crypto assets.
- Statistical distribution and normality testing with Shapiro-Wilk, plus a model-building section covering regression and autoregressive forecasting.
- Historical market events and their impact on a weighted NASDAQ index representation.

## Underlying Data

The notebook uses the following data files and folders in `src/data/`:

- `nasdaq_screener.csv` — market screener reference for NASDAQ tickers
- `nasdaq_company_addresses.csv` — company address data for NASDAQ issuers
- `stock_splits_2000_2025.csv` — stock split history used for price adjustment
- `nasdaq-daily-stock-prices/` — raw per-ticker daily NASDAQ stock data files
- `crypto-currencies-daily-prices/` — raw per-ticker daily cryptocurrency data files

and produces the following files:

- `df_nasdaq_weekly.csv` — aggregated weekly NASDAQ stock prices
- `df_crypto_weekly.csv` — aggregated weekly cryptocurrency prices
- `df_nasdaq_daily.csv` — daily NASDAQ stock prices
- `df_crypto_daily.csv` — daily cryptocurrency prices
- `df_nasdaq_meta.csv` — NASDAQ metadata including sectors, IPO years, market cap, and addresses

## Notebook

The main analysis is documented in `src/analysis_en.ipynb`
