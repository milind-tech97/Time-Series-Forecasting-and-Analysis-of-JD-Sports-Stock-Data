# Time Series Forecasting and Analysis of JD Sports Stock Data

## Overview   
The JD Sports Fashion Plc was established in the year 1981 with a single store in the North West of England. Emerging as one of the leading retailers of Sports Fashion and outdoor brands. Currently it has over 3,400 stores across 38 territories, expanding its presence across the UK, Europe, North America and Asia Pacific. The share price holding of JD sport Fashion Plc contributes to 164.80 GBP (JD Group, 2023). The Time Series Dataset chosen for the coursework is the stocks most active of “JD Sports Fashion Plc (JD. L)”. As per the requirement the historical price of five years is chosen along with the monthly frequency contributing in total of 60 observations from the time range between ‘2019-01-01’ to ‘2023-12-01’. The main focus of the coursework is to analyse the financial time series dataset using python with the time series methods like Naive Method, Average Historical method, Simple Average Method, Simple Exponential Smoothing Methods, Holt’s Linear method, Holt Winters method, ARIMA and SARIMA so on. To provide a better understanding of the methods being used and to provide a better evaluation of the analysis being carried out. 

## Dataset  
The dataset contains **monthly stock price data** of JD Sports for the period **January 2019 to December 2023**. It includes 60 observations, with metrics like close prices, analyzed for trends, seasonality, and noise components.

## Forecasting Methods  
- **Naive Method**  
- **Average Historical Method**  
- **Simple Moving Average**  
- **Exponential Smoothing** (Single, Holt’s Linear, Holt-Winters)  
- **ARIMA/SARIMA**

## Performance Metrics  
- **Mean Absolute Percentage Error (MAPE)**  
- **Root Mean Squared Error (RMSE)**  
- **Mean Absolute Error (MAE)**  

## Key Findings
- **Naive and Historical Average methods showed moderate performance.**
- **Holt's Linear Trend and Simple Moving Average performed best with the lowest MAPE.**
- **ARIMA and SARIMA models struggled to fit the dataset due to stationarity issues.**

## Conclusion
In conclusion, by applying all the time series forecasting methods on the time series data of JD Sports Fashion plc we could notice that the Simple Moving Average Method and Holt’s Linear Method provided a better result with the lower MAPE values compared to all the other forecasting methods. But for the time series data of JD sports fashion Plc, we fail to apply complex models including ARIMA and SARIMA as the Auto-regressive (AR) and Moving Average (MA) is null. Hence, the time series data would better suit the Simple Moving Average Method and Holt’s Linear Method of forecasting.
