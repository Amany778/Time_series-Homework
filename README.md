# Canadian dollar versus the Japanese yen exchange rate forcast using time series

This script will test the different time series tools in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.

Files
Time-Series Starter Notebook
Linear Regression Starter Notebook
CAD/JPY Data CSV File


## Time-Series Forecasting
  Decomposition using a Hodrick-Prescott filter (decompose the settle price into trend and noise).

  Forecasting returns using an ARMA model.

  Forecasting the exchange rate price using an ARIMA model.

  Forecasting volatility with GARCH.

We use the results of the completed time series analysis and modelling to answer the following questions:

Based on your time series analysis, would you buy the yen now?
Is the risk of the yen expected to increase or decrease?
Based on the model evaluation, would you feel confident in using these models for trading?


## Linear Regression Forecasting
In this notebook, we build a Scikit-Learn linear regression model to predict CAD/JPY returns with lagged CAD/JPY futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
  The following steps are performed:
    1.  Data preparation (creating returns and lagged returns, and splitting the data into training and testing data)
    2. Fitting a linear regression model.
    3. Making predictions using the testing data.
    4. Out-of-sample performance.
    5. In-sample performance.

  The results of the linear regression analysis and modelling are used to answer the following question:

    Does this model perform better or worse on out-of-sample data compared to in-sample data?

