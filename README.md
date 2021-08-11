# Covid-19-forecasting
We will be able to find the rate of spread of the disease in the upcoming days with the help of regression analysis models and forecast of COVID-19 in India with the next days for better management for doctors and various government organizations.

We used "Rolling Forecast ARIMA" model to do the forecasting.

Following are the steps that we followed to do the forecasting:

1) We have collected time series data from github of confirmed cases, recovered cases ,death
cases.

2) We dropped insignificant columns such as ‘Lat’, ‘Long’, ‘Country/Region’ , ‘Province/State.
Since the dataset for active cases was not available, we prepared the dataset of active cases by:
active = confirmed -(recovered + death).

3) We have collected data from 22 jan to today and we are focusing on India.So we have filtered
out the data for India only.

4) Tried different model of data analysis and modeling like SIR model, ARIMA model. SIR model didn't work because it only works for a small population. So, finally we incorporated Rolling Forecast Arima model

5) After predicting, we visualized our raw data and the predicted data using different graphs.


NOTE:-
1) DS250_Project.ipynb: Run the file DS250_Project.ipynb
2) Final_Forecasting.png: See the final graph of forecasting for 15 days
3) Covid-19_Analysis_presentation.pdf: See the pdf to understand the project in depth.
