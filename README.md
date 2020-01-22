# Google_Stock_Price_Prediction_LSTM
## Google Stock Price Prediction Using RNN - LSTM

Lately the amount of machine learning applications has been growing exponentially with the new state-of-the-art models and techniques that have made the impossible, possible.
And one of these application is stock market prediction, so in this article we are going to dive deep into how we could use deep learning and more precisely one of the most famous recurrent neural networks : LSTM, in order to perform stock market prediction. But before we start, it is necessary to mention that stock market prediction is not an easy task since the prediction part could be divided into two : fundamental analysis (sales, earning, profits, …) and technical analysis (historical price, …). Which means numerous factors could affect the stock price trends, but in this tutorial we are going to use only time series forecasting using the historical price of a given stock.

## What is RNN . 
Recurrent Neural Networks can Memorize/remember previous inputs in-memory When a huge set of Sequential data is given to it.

These loops make recurrent neural networks seem kind of mysterious. However, if you think a bit more, it turns out that they aren’t all that different than a normal neural network. A recurrent neural network can be thought of as multiple copies of the same network, each passing a message to a successor.

Different types of Recurrent Neural Networks.

* Image Classification
* Sequence output (e.g. image captioning takes an image and outputs a sentence of words).
* Sequence input (e.g. sentiment analysis where a given sentence is classified as expressing a positive or negative sentiment).
* Sequence input and sequence output (e.g. Machine Translation: an RNN reads a sentence in English and then outputs a sentence in French).
* Synced sequence input and output (e.g. video classification where we wish to label each frame of the video) . 

