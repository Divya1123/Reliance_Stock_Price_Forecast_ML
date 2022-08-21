# Reliance_Stock_Price_Forecast_ML
Data Science project to forecast stock price of Reliance Industries. Stock price forecast is a time series forecasting problem.

# Packages 
Python is required for this project. Below are the python libraries used:
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Tensorflow
* Keras

This project was built using [Google Colab](https://colab.research.google.com/).

# Data
Dataset used is `Reliance_stock_price.csv` historic dataset of last 1 year. This dataset consists of 248 data points. 

"close " feature is the stock price and will be used to create "reliance price" dataset to create model.

# Code
Code template is provided in `Reliance_Stock_Price_Prediction.ipynb`. For this time series forecast problem, I used SimpleRNN and LSTM model. In this project we have also taken care of overfitting using Dropout. 

Successfully built model that forecast stock price and achieved `Mean Squared Error = 0.0239616018978634`.





