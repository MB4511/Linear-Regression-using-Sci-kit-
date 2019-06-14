# Linear-Regression-using-Sci-kit-

# Objective

The aim of this repository is to analyze a weather data with a speciific task of predicting temperature based on certain features such as 
humidity, wind speed etc using Linear Regression method in Python. 

# Theory

Linear Regression is used to analyze the strength of relationship between the dependent and the independent variables. I chose this dataset
since temperature is a continuous variable and the predictors are linear to the outcome i.e. temperature. 

# Workflow

The script contains codes for reading the csv file, examining the dataset using certain functions in pandas, splitting the dataset into train
and test for creating a predictive linear regression model, fitting the model and finally interpreting the model based on few important metrics such as
RMSE, MAE and r-squared value for the model.

# Results

The linear regression model gives an impressive r-squared value of 0.99 which verifies the highly linear relationship between temperature and
predictors such as wind speed, humidity, apparent temperature etc. 

Also, the rmse value is 0.95 which signals that the predictions are just off by 0.95 degree celsius. 
