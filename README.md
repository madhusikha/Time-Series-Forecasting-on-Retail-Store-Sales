# Time Series Forecasting on Retail Store Sales

This project encompasses an empirical study aimed at forecasting retail store sales using diverse time series forecasting methods. The dataset comprises an extensive collection of 3,000,888 records, encompassing sales details from 54 different stores and 83,488 transactions. Our primary objective was to analyze sales components, such as trend and seasonality, and assess the performance of various forecasting models implemented in R programming.

To achieve this, we conducted preprocessing tasks, including data conversion into the tsibble format and modifications to column data types. Additionally, exploratory data analysis was carried out, resulting in informative visualizations, such as transaction data by store and date, correlations between sales and transactions, and box plots and line charts illustrating monthly trends.

Furthermore, we employed several forecasting methods, including seasonal naive, exponential smoothing (ETS), ARIMA, and Prophet. Each method was evaluated based on its ability to capture underlying patterns in the sales data and provide accurate predictions. The models underwent training and testing using appropriate time series evaluation techniques, with a particular emphasis on the root mean square error (RMSE) metric for assessing forecasting accuracy.
Through comprehensive analysis and comparison, the Prophet model demonstrated superior performance in terms of RMSE values for the test data.

* Please refer .html file for the full project implementation with all the plots.*
