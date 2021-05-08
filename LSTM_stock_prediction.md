#LSTM Stock Predictor Assignment

The goal of the assignment was to build and evaluate deep learning models using both closing prices and FNG values, which is an indicator of public sentiment for cryptocurrencies). The notion was to see if FNG values can act as a better signal for cryptocurrencies compared to closing price data. 

The assignment utilized historic Bitcoin closing and sentiment data for the recurrent neural network model. 

The lstm_stock_predictor_fng relies on FNG values to predict the closing price of bitcoin while lstm_stock_predictor_closing uses closing price data to predict the next closing price. 


Each model used 70% of the data for training and 30% for testing. 

* Which model has a lower loss?
In comparison, the closing price model registered lower loss than the FNG model

* Which model tracks the actual values better over time?
The closing price model tracks the actual values better over time. 


* Which window size works best for the model?

FNG 10 day window loss = .1255
Closing 10 day window loss = .0113

FNG 1 day window loss = .098
Closing 1 day window loss = .0020

FNG 5 day window loss = .0875
Closing 5 day window loss =.0070

The window size of 1 day works best for the model.
