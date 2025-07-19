# Final-Project-for-SoC
This is the repository containin the final project for SoC 2025.

# Brief explaination for the running the code and the interpretation 

I have divided my code in the notebook as per various sections on importing downloading, model defining, visualisation,etc.

Starting of I have taking the input regarding the stock to analyse related to the ticker, starting and ending date and the timeframe to analyse for and downloaded the data from yfinance according to it.

Following sections contents the data visualisation using matplotlib.

I have also used to technical indicators like SMA,EMA,MACD, bollinger band and visualised it in order to get the intution for the stock.

Starting of with the LSTM model for the following stock using tensorflow and in build method for LSTM model.

I build a 2 layer LSTM model for the same using the LSTM function of tensorflow.

Along with the dense neutrons layers supporting it.

I then build the model on the training dataset with 50 iteration to get an loss = 0.0025 which is preety less compared to the loss in first iteration which was 0.005 showcasing a good model.

Then predicted the values on the testing dataset with the following results.


calculating the RMSE and the R2 for the data gave the following values on the testing dataset.

R2 Score: 0.9543353175931343

RMSE: 0.05000812092918255

Which is quite good value and hence we can say that our model is quite well trained.

Also through visualization we can see that the model has a good prediction.


