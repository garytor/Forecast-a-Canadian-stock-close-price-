# Forecast-a-Canadian-stock-close-price-

The objective of this project is to forecast 5 days(October 3 - 7, 2022) of stock close prices for Algonquin Power & Utilities Corp.(Ticker: AQN.TO)
The dataset was obtain from Yahoo Financials for the period January 4, 2010 to October 28, 2022.
The Mean Absolute Errors for various models are as follow:

# Fine tune RNN model hyperparameters using univariate dataset
Best model mean absolute error: CAN$2.52

# Fine tune RNN model hyperparameters using multivariate dataset
Best model mean absolute error: CAN$0.39

# Fine tune 1D convolutional/RNN model hyperparameters using multivariate dataset
Best model mean absolute error: CAN$0.42

# Fine tune ARIMA model hyperparameters
Best model mean absolute error: CAN$0.37

The ARIMA model outperform the RNN models.
