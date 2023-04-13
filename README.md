# SimpleStockPrediction-ML-Project

# Intorudction 

Nowadays, the stock market is popular for investment and profit-making. However, its volatility and unpredictability pose challenges for predicting future stock prices. In this study, machine learning (ML) models is used to analyze historical data and make accurate predictions. In this research the implementation of five commonly used ML models for time series data - Linear Regression, Moving Average, Simple Exponential Smoothing, Autoregression, and ARIMA - is used to determine which model performs best in forecasting stock prices. The research question is, ***"Which machine learning model is the best for predicting future stock prices?"***

# Dataset 

The dataset is retrieved for AAPL (Apple) stock, SONY (Sony) and THMO (Thermogenesis) from Yahoo Finance using the yfinance python library. The dataset includes time series data from 2016 to 2022, with seven features: 'Open', 'High', 'Low', 'Close', 'Adj Close', 'Volume', and 'Target'. The main focus is on the 'Open', 'High', 'Low', and 'Close' features, which provide important information about the stock's beginning price, volatility, fluctuation, and ending price for each day. 

# Models

* **Linear Regression**

Linear regression is a popular technique for stock price forecast due to its ease and efficacy. It involves fitting a straight line to data points and finding patterns in past stock values to predict future prices. The equation of a line in two-dimensional linear regression is given by ***y = mx + b***, where y is the predicted variable, x is the independent variable or feature, m is the slope of the line, and b is the y-intercept. Several studies have shown that linear regression can accurately forecast stock values, with the closing price being an important predictor. Linear regression has also been compared to other methods such as support vector regression and decision trees, with varying results in terms of accuracy and computational requirements. When combined with other methods, such as principal component analysis and artificial neural networks, linear regression has been found to be an efficient way to predict stock prices.

* **Moving Average** 

The moving average algorithm is a statistical method used for time series data analysis. It involves calculating the arithmetic mean of a set of values for a certain time period and placing it at the center of that period. The process involves weighting the mean and previous error terms to determine future values. This results in a smooth curve that reveals underlying trends and reduces fluctuations in the data. Moving average is commonly used in finance to analyze stock prices and identify trends and trading signals. The period for the moving average must be carefully chosen before implementing the technique.

* **Smoothing**

Exponential smoothing is a statistical technique used for time series data prediction. It includes three types: simple, double, and triple. Simple exponential smoothing is suitable for short-term forecasting and assumes data fluctuates around a stable mean with no trend. It uses a weighted average of current and previous smoothed observations, with weights decreasing exponentially based on a parameter α. Double exponential smoothing with a trend is used when there is a trend in the data, updating both level and trend components each period. Triple exponential smoothing is employed when there is both trend and seasonality in the data, and it uses an additional parameter and equation to account for seasonality in the Holt-Winters approach.

* **Autoregression**

Autoregression (AR) models are used to evaluate time series data by assuming that the most recent value of a series is a linear function of its earlier values with some random error. An AR model makes predictions about the subsequent value using prior values, with the number of prior values depending on the order of the model. Studies have compared AR models with other methods like artificial neural networks (ANNs) in forecasting, finding that different models perform better depending on the forecasting horizon and complexity of the time series data. AR models can be expanded to include additional elements like patterns or seasonality. Maximum likelihood estimation is commonly used to estimate the parameters of AR models. AR models are commonly used in areas such as finance forecasting and weather forecasting.

* **ARIMA**

ARIMA (Autoregressive Integrated Moving Average) is a popular statistical technique used for time series data analysis in fields like finance and economics. It combines autoregressive (AR) and moving average (MA) models, defined by three parameters: p, d, and q. ARIMA(p,d,q) represents the number of lagged observations for autoregression, the level of differencing for time series stability, and the size of the moving average window, respectively. The ARIMA model has been used for forecasting various economic factors, such as stock market indices, exchange rates, and inflation. It is preferred due to its ease of use, readability, and success in many situations. Accurate forecasts rely on careful parameter selection and data analysis, and ARIMA can be a valuable tool for decision-making in different sectors.



