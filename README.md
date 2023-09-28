# Stock Price Prediction using Machine Learing

I am going to try and predict the future value of Nvidia company stock. I will use a LSTM network to predict the closing stock price using the past stock price. The machine learning technique called Long Short Term Memory is an artificial recurrent neural network architecture used in the field of deep learning.

Using yfinance module to import fianace data from Yahoo Finance. Them creating a new dataframe and training data. We will only be consider the closing market price and predicting the closing market price. Create a data set to train the data that contains the closing price of a certain number of days so that we could do the prediction for the closing price. . The days can to reduce error, for me 160 gave the lowest error so it was choosen. With more testing a more suitable number can be found. 

LSTM model will have two LSTM layers with 200 neurons and two Dense layers, two with 100 neurons and the other with one neuron. Once again again these can be changes to reduce error, but directly reelate to running time. If increased running time will increase. Batch size and epochs can also be increased but will effect running time. 

RMSE is the root mean squared error, which helps to measure the accuracy of the model.
I recieved 11 which I is relatively high from what I have read online. But this was the lowest I can get it without further testing. With more testing a lower RMSE can be achieved. 


Improvements:
Improve the algorithm:
- Decrease RMSE by doing more testing. Changing test data size, increasing step size. Testing different bins and epochs. Aslo adding more layers (aswell as dense layers).

Add in more predictors:
- Early trading/Trading on other exchanges (gives insight to global sentiment).

Economic indicators:
- Use both open and close price in predictions.
- Include Volume in predictions. 
- Interest rates.

Use different algorithm:
- Try something different like an Echo State Network or Random Forest. 
