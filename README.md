## quant-LSTM

*A recurent-based neural network approach to stock price predictions* <br>
*Authors: Ryan, Shimon, Xin (Spencer), Yufeng*

### Motivations:
* LSTM works great on sequential and time series data
* Easy to train on Keras

### Data:
* Gathered using Yahoo Finance API
* Train:Test split of 80:20
* Preprocessed data into multiple windows of sequential n_inputs and 1 sequential output, similar to sliding window


We used 60 days of stock price data (default) to predict the price for the next day (n_input = 60, n_output = 1).

### How to use:
To run the model, type desired parameters into "modeling()". The code will create the LSTM architecture and train automatically on available data. The results will be a time series graph with predictions for the validation dataset.
