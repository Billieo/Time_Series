# Time_Series

# Time-Series Forecasting

- For the Time-series-forcasting we will use historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior of the following.

- Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).

![image](https://user-images.githubusercontent.com/80086711/137606029-76fead3c-c822-4b64-9e3f-9a677693b236.png)
![image](https://user-images.githubusercontent.com/80086711/137606054-9e0855a8-57bc-4fda-91e8-017834783105.png)

- Forecasting Returns using an ARMA Model.

![image](https://user-images.githubusercontent.com/80086711/137605978-e83b9979-5b2c-479d-ab04-9b549862b672.png)


- Forecasting the Settle Price using an ARIMA Model.

![image](https://user-images.githubusercontent.com/80086711/137605962-0c4e87ae-08c8-4746-a8e1-e08b304dbc76.png)


- Forecasting Volatility with GARCH.

![image](https://user-images.githubusercontent.com/80086711/137605920-ed3a66ec-9646-4d7b-9901-376e30b4a125.png)




# Conclusions
- Based on the time series analysis, I will not buy Yen because the p-value is greater than 0.05.
- The risk of the yen expected to increase.
- Based on the model evaluation, I do not feel confident in using these models for trading because all the p-values are greater than 0.05.
