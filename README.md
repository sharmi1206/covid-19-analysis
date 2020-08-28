covid-19-analysis
Covid-19 India's statewide analysis with census data 2011 and Kaggle data

Notebook covid-19-data-discovery.ipynb contains analysis of statewise data (Population density, Literacy rate, Elderly population Rate, Number of International Airports per State, How busy the international Airports are in terms of number of passengers traveling per million through it).

covid-19-data-discovery.ipynb contains number of districts effected per state, number of Red , Green , Orange zones received till 1st May and their relation with number of Active , Confirmed cases and number of deaths.

The co-relation map of all the above stated features with number of Active , Confirmed cases and Number of deaths and Recovery rates.

covid-19-tseries-pred.ipynb. contains the following regression and Time series analyis.

1. Linear Regression
2. Polynomial regression with lasso
3. Simple and Exponential Smoothing 
4. Holt's Winter Model
5. Dickey-Fuller test
6. AR, MA and ARIMA Models
7. Auto AR, MA, ARIMA and SARIMA Models
8. AR, MA, ARIMA, SARIMA  using VARMAX Modeling
9. Facebook's Prophet Model

tseries_analysis_full_singlestep_forecats.ipynb contains deep learning bassed analysis using 1.LSTM , 2. CNN and 3. LSTM+CNN. It's single step time series based prediction using data from folder covid-19-latest_6_june.  

ts_deeplearning_mstep_forecats.ipynb contains deep learning bassed analysis using 1.LSTM , 2. CNN, 3. LSTM+CNN and 4.CONV2LSTM.  It's multi-step time series based prediction using original data from folder covid-19-latest_6_june. However the processed data are stored in all_states folder from the previous jupyter notebook (tseries_analysis_full_singlestep_forecats.ipynb).

In the last 2 notebooks, you need to change the "path" variable to the folder directory where covid-19-analysis is stored

