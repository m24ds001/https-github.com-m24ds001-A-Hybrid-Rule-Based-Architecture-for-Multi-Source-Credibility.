# CreditTrust Financial Dataset

This repository contains the curated multi-source financial dataset
used in the manuscript submitted to *Expert Systems (Wiley)*.

## Dataset Description
The dataset consists of daily stock closing prices collected from
four independent public financial data providers:

- Yahoo Finance
- Finnhub
- Polygon.io
- Alpha Vantage

The data was collected programmatically using official APIs and
represents real-world financial observations.

Due to API rate limits and licensing constraints, the publicly released
dataset represents a curated and processed snapshot that preserves
the structure and characteristics required to reproduce the reported
results.

## File Included
- `hcra_financial_dataset.csv` – Curated multi-source financial dataset

## Columns
- `date` : Trading date (YYYY-MM-DD)
- `stock` : Stock ticker symbol
- `yahoo_price` : Closing price from Yahoo Finance
- `finnhub_price` : Closing price from Finnhub
- `polygon_price` : Closing price from Polygon.io
- `alphavantage_price` : Closing price from Alpha Vantage
- `ground_truth` : Reference price used in analysis

## Usage
This dataset is provided for academic research and reproducibility
purposes related to the accompanying manuscript.

## License
Creative Commons Attribution 4.0 International (CC BY 4.0)
