# Time Series Forecasting with ARIMA & SARIMA Model
## Description
This project demonstrates the process of performing a time series forecast on electricity generation data using the ARIMA (AutoRegressive Integrated Moving Average) and SARIMA model. Both are suitable for time series data exhibiting non-stationarity, where differencing can be applied to remove trend or seasonal structures.

## Procedure
1. Initial Analysis: Conduct a brief analysis to determine the stationarity of the series and identify appropriate parameters for the ARIMA model.
2. Stationarity Check: Use the Augmented Dickey-Fuller (ADF) test to assess stationarity. If necessary, apply differencing to achieve stationarity.
3. Parameter Identification: Identify the differencing order (d) and autoregressive (p) and moving average (q) parameters using the autocorrelation function (ACF) and partial autocorrelation function (PACF) plots.
4. Model Fitting: Fit an ARIMA/SARIMA model with the determined parameters to the data.
5. Forecasting: Forecast future values of electricity generation using the fitted ARIMA/SARIMA model.

## Findings
The ADF test suggests the series is non-stationary, requiring differencing.
Further differencing still shows signs of seasonality, hence SARIMA model is required.
The fitted models are:
ARIMA(3,1,3) 
SARIMA(2,1,0)(1,0,2)[12]  

## Recommendations
1. Monitoring and Adjustment: Regularly monitor actual electricity generation against forecasts to ensure grid reliability.
2. Capacity Management: Utilize forecasts to manage capacity and ensure adequate generation capacity.
3. Investment Planning: Consider forecasts in investment planning for renewable energy sources and infrastructure upgrades.
4. Demand Response Initiatives: Implement demand response initiatives during forecasted high demand periods to maintain grid stability.

These forecasts provide valuable insights for planning and decision-making in the energy sector, aiding stakeholders in anticipating future needs and adjusting strategies accordingly.
