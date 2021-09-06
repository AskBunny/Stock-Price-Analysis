# Stock-Price-Analysis
We’ve explored just the tip of the iceberg for the stock market analysis as technical analysis of the stock is a vast field using python.

## Method

In terms of doing this project, we’ve used basic statistics for analysis and the following are the libraries installed beforehand which can easily be downloaded with the help of the pip function.

### Libraries used

- **Yahoo Finance:** To download stock data
- **Pandas:** To handle data frames
- **Numpy:** Numerical Python
- **Matplotlib:** Plotting graphs

## Intended experiment

All the stocks are traded on exchanges and their prices are constantly changing due to their demand and supply in the market. If a stock is in high demand and low in supply i.e., more people want to buy it and fewer people are willing to sell it then the price for the stock will go up and similarly if the stock is in low demand and high on supply which means people more people are ready to sell it but fewer people are willing to buy it then its prices go down.

This project helps us in understanding the open price for previous years of a stock, volatility which tells the risk associated with that stock and average volume of trades in a day.

## Analysis & Visualization

To understand a stock’s short-term and long-term behavior, there are couple of analysis can be performed.

### 1. Exploratory Analysis: 
The tells the open stock prices for these three companies via line graph by using matplotlib library in python.

### 2. Volume of Stock traded:
Volume of stock traded for a particular time

### 3. Market Capitalisation:
Only volume or stock prices do not provide a comparison between companies. The total worth of a firm is calculated by multiplying the stock price and the number of shares outstanding. This measure is significant since it provides information about a company's size and how it has changed over time. The market capitalization of companies changes daily with movement in their stock price.

### 4. Moving Average:
A moving average (MA) is a stock indicator that is commonly used in technical analysis. The reason for calculating the moving average of a stock is to help smooth out the price data over a specified period of time by creating a constantly updated average price.

### 5. ARIMA Model: 
An ARIMA model is a class of statistical models for analyzing and forecasting time series data. ARIMA stands for AutoRegressive
Integrated Moving Average. Briefly, they are:

**Autoregression (AR):** refers to a model that shows a changing variable that regresses on its own lagged*, or prior, values. Integrated (I): represents the differencing of raw observations to allow for the time series to become stationary (i.e., data values are replaced by the difference between the data values and the previous values).
**Moving average (MA):** incorporates the dependency between an observation and a residual error from a moving average model applied to lagged observations. An ARIMA model is characterized by 3 terms p, d, q:

• p: the number of lag observations in the model; also known as the lag order.

• d: the number of times that the raw observations are differenced; also known as the degree of differencing.

• q: the size of the moving average window; also known as the order of the moving average.

*Lag is the "Distance" (in time) between the events you link together. So, a "Lag 1" is the preceding event. In case of a monthly metrics, Lag 12 is a year before. In case of a daily metric, Lag 7 is the same day the week before.
