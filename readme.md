Tata Motors stock price prediction

This prediction model uses Random forest algorithm for predicting the data. The data has been split into windows and labels to make it a supervised ML problem.
The prediction is done by considering previous 7 days of stock prices to predict the 8th day. The data has been split in training and testing data and labels accordingly.

The model is trained on historic data in the time frame of 6/4/2005 to 24/3/23.

Multiple stock indicators such as:
1) RSI (Relative Strength Index)
2) Exponential Moving Average (EMA)
3) MACD (Moving Average Convergence Divergence)
(Calculated only for predicted data)
Are used to determine BUY or SELL signal of the stock.

These are calculated using the ipynb files with their respective name.

The final model is in the file *Tata_motors_Stock_prediction.ipynb*


Visualising model predictions:
1) On complete dataset: 
   ![image](https://user-images.githubusercontent.com/97504422/227954935-240deeec-051e-4dc0-b137-4a41fce67fbd.png)

2) Model performance on test data
   ![image](https://user-images.githubusercontent.com/97504422/227955133-7d761dc6-1c96-488d-97e3-d3b7c8acc092.png)

Predicted data with Buy Tags for visualisation:

![image](https://user-images.githubusercontent.com/97504422/227955428-46ad706a-afbf-4d5f-a6c3-5bf0f7880866.png)


*predictions_final.csv* is the final file with all the predictions, indicator values and BUY/SELL Action tags


STOCK PREDICTION FOR AAPL USING LSTM

The prediction for AAPL stock is also done using LSTM model.
Steps similar to Tata motors model can be used to generate buy/sell signals and calculating the indicators

LSTM model accuracy->

![image](https://user-images.githubusercontent.com/97504422/228040109-fbd76dc1-52c3-41cc-9662-3348a0d7e2a8.png)

(Above representation is a comparision beetween test labels and predicted data)





