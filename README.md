# Stock Price Prediction Using LSTM

This project aims to predict the closing stock price of Meta Platforms, Inc. (META) using an LSTM (Long Short-Term Memory) neural network, leveraging historical stock price data.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)


## Overview

This project involves:

1. Reading historical stock price data for Meta (META) from July 19, 2023, to July 19, 2024.
2. Training an LSTM model to forecast the stock's closing price.
3. Evaluating the model's performance and predicting the closing price for July 20, 2024.

## Dataset

The dataset consists of Meta's historical stock prices in CSV format, which includes `Open`, `High`, `Low`, `Close`, `Volume`, and `Adjusted Close` prices. You can download the data from [MarketWatch](https://www.marketwatch.com/investing/stock/meta/download-data) for the specified date range.

Ensure the dataset is placed in the appropriate directory (`data/meta_stock_data.csv`) before running the code.

## Model

This project uses an LSTM model to predict the closing stock price of Meta. The LSTM model is selected due to its capability to capture long-term dependencies in sequential data, making it suitable for time-series forecasting.

### Steps Involved:

1. **Data Preprocessing**: The data is normalized and split into training and testing sets.
2. **Model Building**: An LSTM model is constructed using Keras/TensorFlow.
3. **Model Training**: The model is trained on the historical stock data.
4. **Model Evaluation**: The model's performance is evaluated using Mean Squared Error (MSE).
5. **Prediction**: Predict the closing stock price for a future date.

### Results:
1. **Root Mean Squared Error**: 15.828
2. **mean Absolute Error**: 11.8122
3. **R2 Score**: 0.4939

