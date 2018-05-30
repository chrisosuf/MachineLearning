
# Stock Trend Prediction

This is a stock trend prediction project using an LSTM recurrent neural network. It aims to predict the next day price using previous trends of high, low, and open prices.

This project includes a file showing an output that is clearly biased and deceiving. I have targeted this problem to be the fact that the next day price also takes into account the correct price of the day prior and not solely the predictions of the testing data -  a problem to be looked out for in future applications to avoid any bias and overfitting.

### Authors

* Chris Osufsen 

### Running

Run <code>jupyter notebook</code> in terminal and open the notbook. The main file is the <code>Predict_Stocks</code> (1).ipynb file.

### Acknowledgments

* Much of this code has been inspired by and learned from Siraj Raval's image prediction tutorials and Keras documentation. The lstm.py file has been utilized from llSourcell (Ravel's github) and altered to effectively be used in my program. This file is part of a coding challenge by Ravel.
