# Samsung Stock Price Prediction using Regression

This project implements a stock price prediction model for Samsung Electronics (Ticker: `005930.KS`) using historical stock data. The objective is to predict the closing stock price for the next day based on the previous day's closing price. This model uses **Linear Regression** to make the predictions.

## Project Overview

In this project, we utilize **Yahoo Finance (yfinance)** to download historical stock data for Samsung Electronics. We then preprocess the data, build features, and apply a regression model to predict future stock prices.

## Key Features:
- **Data Collection**: Historical stock data for Samsung Electronics (from Yahoo Finance) is downloaded using the `yfinance` library.
- **Data Preprocessing**: Only the "Close" price is used for prediction, with the previous day's closing price acting as the feature.
- **Regression Model**: A **Linear Regression** model is trained on the data to predict the next day's stock price.
- **Evaluation**: The model's performance is evaluated based on its predictions.

## Requirements

To run this project, you need to install the following Python libraries:

- `yfinance` (for downloading stock data)
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `scikit-learn` (for machine learning models)
- `matplotlib` (for data visualization)
