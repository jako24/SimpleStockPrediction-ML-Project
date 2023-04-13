# SimpleStockPrediction-ML-Project

# Intorudction 

Nowadays, the stock market is popular for investment and profit-making. However, its volatility and unpredictability pose challenges for predicting future stock prices. In this study, machine learning (ML) models is used to analyze historical data and make accurate predictions. In this research the implementation of five commonly used ML models for time series data - Linear Regression, Moving Average, Simple Exponential Smoothing, Autoregression, and ARIMA - is used to determine which model performs best in forecasting stock prices. The research question is, ***"Which machine learning model is the best for predicting future stock prices?"***

# Dataset 

The dataset is retrieved for AAPL (Apple) stock, SONY (Sony) and THMO (Thermogenesis) from Yahoo Finance using the yfinance python library. The dataset includes time series data from 2016 to 2022, with seven features: 'Open', 'High', 'Low', 'Close', 'Adj Close', 'Volume', and 'Target'. The main focus is on the 'Open', 'High', 'Low', and 'Close' features, which provide important information about the stock's beginning price, volatility, fluctuation, and ending price for each day. 

# Models

* **Linear Regression**

Linear regression is a popular technique for stock price forecast due to its ease and efficacy. It involves fitting a straight line to data points and finding patterns in past stock values to predict future prices. The equation of a line in two-dimensional linear regression is given by 
                              ***y = mx + b***
, where y is the predicted variable, x is the independent variable or feature, m is the slope of the line, and b is the y-intercept. Several studies have shown that linear regression can accurately forecast stock values, with the closing price being an important predictor. Linear regression has also been compared to other methods such as support vector regression and decision trees, with varying results in terms of accuracy and computational requirements. When combined with other methods, such as principal component analysis and artificial neural networks, linear regression has been found to be an efficient way to predict stock prices.

* **Moving Average** 
* **Smoothing**
* **Autoregression**
* **ARIMA**




