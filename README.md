# Forecasting-Stock-Prices-using-ARIMA

To predict the prices of HCL, I used the ARIMA model. In order to fit the model and generate predictions for each element on the test set, we divide the training dataset into train and test sets.


ARIMA models is one of statistical technique could be used to forecast time series data.In ARIMA models, one has to decide on the order in such a way that error is reduced.

Function used:

Auto ARIMA: Automatically discover the optimal order for an ARIMA model.
The auto arima function returns a fitted ARIMA model after attempting to determine the ARIMA model's most ideal parameters. This function is based on the forecast::auto.arima function that is frequently used in R.
The auro arima function fits models within defined start p, max p, start q, and max q ranges after performing differencing tests (such as Kwatkowski-Phillips-Schmidt-Shin, Augmented Dickey-Fuller, or Phillips-Perron) to establish the order of differencing, d. After executing the Canova-Hansen to discover the best order for seasonal differencing, D, auto arima additionally tries to identify the best P and Q hyper-parameters if the seasonal optional is enabled.

 In this model we do forecast the future stock prices and also check the commonly used accuracy metrics to judge forecast results.







