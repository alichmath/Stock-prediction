# Stock Price Prediction
In this repository, we will build a model for predicting stock price of AAPL using a deep neural network with 4 layers. We will use two LSTM layers with 128 and 64 nodes followed by 2 dense layers of 25 and 1 nodes. 

### Training and Test Set
We use 5 years of AAPL price for prediction and we will set our training data to be the closing price of AAPL for first 95% of the 5 years and  test data to be the closing price for the last 5% of the time. 

### Results and Next Steps
Results, as shown in the last figure, show a very close distance between prediction and the close price. This shows that having a long position for AAPL in that period would have been a good strategy. Next steps for this model would be to use more layers of LSTM or RNN (or other layers) to be able to have a better prediction of the stock price. Also this model can definitely be used for other commodities or securities. 

Another direction would be to consider more epochs for training which would give a better result usually (e.g. I have tried 10 epochs and 80% of training data and it was able to give a pretty good prediction of stock price).
