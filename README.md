# Stock-Price-Prediction
## (Predicting google stock price by using recurrent neural network)

Stock market prediction is the act of trying to determine the future value of a company stock
or other financial instrument traded on an exchange.
The successful prediction of a stock's future price could yield significant profit.
The efficient-market hypothesis suggests that stock prices reflect all currently available information and any price changes that are not
based on newly revealed information thus are inherently unpredictable.

# Recurrent Neural Network(LSTM)  with Keras Framework
In this project using recurrent neural network,Google opening stock price for month January(2017) is predicted.
Last 5 year's data of Google stock price is used for analysis.

## About RNN
Classic RNNs have short memory, and were neither popular nor powerful for this exact reason. But a recent major improvement in Recurrent Neural Networks gave rise to the popularity of LSTMs (Long Short Term Memory RNNs) which has completely changed the playing field.


Predicted stock price for Google's trending Stock data
1. Successfully predicted Google stock price by using last 5 year's data of Google stock price.
2. Use of RNN(LSTM) was implemented alongside with Keras framework producing some good results.

Technology Used: Deep Learning , RNN , Machine Learning , LSTM

I have taken here two timestamps to test the accuracy of the model.
With 1TS, we got a very good result with the accuracy reaching to almost 93 percent but actually fact is this model is predicting stock price
of the very next day taking the stock price of the present day as input.

So,in the next step I tried to train the same model with 60TS, as expected model does not perform very well this time which you can even realize
by looking into the figures of both (With 60TS and with 1TS respectively).

![stock1](https://user-images.githubusercontent.com/30611434/42944730-165abd64-8b84-11e8-8381-98649bcb99c5.png)

![stock2](https://user-images.githubusercontent.com/30611434/42944743-1ae688d6-8b84-11e8-9e7c-b49642c2e1fe.png)

### Thankuu...
