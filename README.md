# Stock Price Prediction using Machine learning

I am going to try and predict the future value of Nvidia company stock. I will use an LSTM network to predict the closing stock price using the past stock price. The machine learning technique called Long Short Term Memory is an artificial recurrent neural network architecture used in the field of deep learning.

Using yfinance module to import finance data from Yahoo Finance. Them creating a new dataframe and training data. We will only consider the closing market price and predict the closing market price. Create a data set to train the data that contains the closing price of a certain number of days so that we can make the prediction for the closing price. The days can reduce error, for me, 160 gave the lowest error so it was chosen. With more testing, a more suitable number can be found. 

The LSTM model will have two LSTM layers with 200 neurons and two Dense layers, two with 100 neurons and the other with one neuron. Once again these can be changed to reduce error, but directly related to running time. If increased running time will increase. Batch size and epochs can also be increased but will affect running time. 

RMSE is the root mean squared error, which helps to measure the accuracy of the model.
I received 11 which is relatively high from what I have read online. But this was the lowest I can get it without further testing. With more testing, a lower RMSE can be achieved. 


Improvements:
Improve the algorithm:
- Decrease RMSE by doing more testing. Changing test data size, increasing step size. Testing different bins and epochs. Aslo adding more layers (aswell as dense layers).

Add in more predictors:
- Early trading/Trading on other exchanges (gives insight to global sentiment).

Economic indicators:
- Use both open and close price in predictions.
- Include Volume in predictions. 
- Interest rates.

Use different algorithms:
- Try something different like an Echo State Network or Random Forest. 
