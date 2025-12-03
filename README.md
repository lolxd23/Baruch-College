# CIS9650 Assignment 2 - Stock Data Analysis

## Student Information
- **Name:** Hajara Eve Muzammal
- **Student ID:** 24758122
- **Date:** December 2nd, 2025

## Project Overview
This project reads a stock CSV file, sorts the data by ticker symbol, then computes basic stats and technical indicators for each stock.

Using Python's built-in csv module, the program loads the CSV file, organizes entries by ticker, determines the highest high and lowest low, and uses NumPy to compute the 30-day SMA & EMA, latest daily return, and 20-day volatility.

## How to Run
1. Make sure **`stock_data_july_to_september.csv`** is in the same folder as the script
2. Run the Python script:
```bash
python hajara_muzammal_final.py
```

Or in an IDE, simply run the file.

## Data File
**Filename:** `stock_data_july_to_september.csv`
- **Format:** Comma-separated values (CSV format)

## Assumptions
- Low, High, Ticker, and Close are the necessary columns in the file. Additionally, we can presume that there was sufficient stock data to carry out computations and that NA values were eliminated from the rows. 

