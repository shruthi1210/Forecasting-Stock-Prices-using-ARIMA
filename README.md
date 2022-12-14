# Forecasting-Stock-Prices-using-ARIMA

To predict the prices of HCL, I used the ARIMA model. Using a Python tool, we will perform the forecast. In order to fit the model and generate 

predictions for each element on the test set, we divide the training dataset into train and test sets [training (70%) and test (30%)].

Given the reliance on observations from earlier time steps for differencing and the AR model, a rolling forecasting approach is necessary. In 

order to achieve this, we recreate the ARIMA model each time a fresh observation is obtained.

ARIMA models is one of statistical technique could be used to forecast time series data.

Time series data have trend, seasonality/cyclicality and noise components.

In ARIMA models, one has to decide on the order in such a way that error is reduced.





The packages that we are using are:

pandas – This package helps us data handling and data manipulations easy

datetime – Used to handle date and time objects

matplotlib - Used for data visualization and plotting 2D graphics

statsmodels- Used to explore data, estimate statistical models, and perform statistical tests
