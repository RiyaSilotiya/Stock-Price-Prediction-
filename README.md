# Stock-Price-Prediction

## Introduction
Welcome to the Stock Price Prediction project repository! This self-project was undertaken with the main objective of developing a stock price prediction model using Long Short-Term Memory (LSTM) based Recurrent Neural Networks (RNNs). The project focuses on predicting future stock prices of Apple Inc. based on historical stock price data.

## Dataset
The historical stock price data of Apple Inc. was used for training and testing the stock price prediction model.
Stock traders mainly use three indicators for prediction: OHLC average (average of Open, High, Low and Closing Prices), HLC average (average of High, Low and Closing Prices) and Closing price, In this project, OHLC average has been used.

## Data Pre-processing
 The dataset has been converted into OHLC average, resulting in a one-column dataset. This one-column dataset was then transformed into a two-column time series format, where the first column represents the stock price at time t, and the second column represents the stock price at time t+1. The stock price data was preprocessed to handle missing values, normalize the data, and create sequences with 10 timesteps for training the LSTM model. Scaling and inverse scaling techniques were implemented to enhance the accuracy of the predictions.

## LSTM-based RNN Model
Long Short-Term Memory (LSTM) is a type of Recurrent Neural Network (RNN) designed to capture long-term dependencies in sequential data. In this project, we designed and configured an LSTM model with appropriate timesteps to learn patterns and predict future stock prices.

## Model Training
The LSTM-based model was trained using the preprocessed historical stock price data. The model was optimized using RMSProp optimizer and mean squared error loss functions and evaluation metrics.

## Model Evaluation
The performance of the stock price prediction model was evaluated using the Mean Absolute Error (MAE) metric. 

## Results
The LSTM-based stock price prediction model successfully achieved a mean absolute error (MAE) of 1.51, showcasing its effectiveness in predicting future stock prices of Apple Inc. This model has potential implications in assisting investors and traders in making informed decisions regarding stock trading and investment strategies.
