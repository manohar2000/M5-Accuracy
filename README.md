This is the repository for M5 forecasting accuracy competition on Kaggle. M5 Forecasting - 
Accuracy is a forecasting problem that aims at forecasting the daily sales for the next 28 days using features like events around the specified date, location of a store, and the item category.
We tackled this problem by applying various models starting from stats models to LSTM's The evaluation metric was WMRSE and the following are the results we achieved:
1) Prophet: 0.634
2) ARIMA: 0.780
3) LightGBM: 0.496
4) LSTM: 0.910

All the prediction csv files are present in the submission folder. All the python code are present in the scripts folder.


The dataset can be found at : https://www.kaggle.com/c/m5-forecasting-accuracy/data


