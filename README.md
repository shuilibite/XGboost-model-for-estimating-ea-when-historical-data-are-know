# XGboost-model-for-estimating-ea-when-historical-data-are-know
Authors: Rangjian Qiu, Lifeng Wu

to run the program, click the "xgboost_daily_ea_estimation"

notice
1. to run the model, make sure you have installed the package 
packages('openxlsx')
packages('xgboost')
packages('lubridate')

2.to load the XGBoost model and xlsx file of trainning and testing data
please change the file path in your computer

3. prepare your training data as follows in excel
1         2         3             4
year    Tmax  Tmin and RH

 and finally testing data as 
1         2         3           
year    Tmax  Tmin 

