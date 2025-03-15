# Stock Market Predictions with LSTM

## Overview

This project implements a Long Short-Term Memory (LSTM) model for predicting stock price movements using historical data. LSTM networks are powerful for time-series forecasting, making them a great choice for stock market prediction.

## Features

- Fetches historical stock data from Alpha Vantage API.
- Preprocesses data by normalizing and splitting it into training and test sets.
- Implements one-step-ahead prediction techniques such as averaging and exponential moving average (EMA).
- Utilizes an LSTM model to predict stock price movements multiple steps into the future.
- Generates visualizations of stock trends and model predictions.

## Model Architecture

The LSTM model includes:

- Three LSTM layers with dropout regularization to prevent overfitting.
- A fully connected output layer for stock price prediction.
- Mean Squared Error (MSE) as the loss function.
- Adam optimizer for efficient training.

## Results

- The LSTM model performed better than simple averaging in predicting stock price movements.
- **MSE improvement**: The LSTM achieved lower MSE compared to moving average techniques.
- **Limitations**: Predicting stock prices accurately remains challenging due to market volatility.

## Key Takeaways

- Stock price prediction is difficult because of market unpredictability.
- LSTMs can detect trends, but they shouldn't be blindly relied on for financial decisions.
- Tuning hyperparameters is essential for better performance.
- EMA and moving averages serve as good baselines before implementing deep learning models.