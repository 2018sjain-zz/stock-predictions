# stock-predictions
Using TensorFlow machine learning and Twitter sentiment analysis to predict stock trends

### Basics
"stock-predict.py" runs through these steps:

1. Requests an input of a NASDAQ stock quote.
2. Downloads the last year's historical data for that stock using Google's resources.
3. Trains a neural network that the historical data to predict the stock's closing price for tomorrow.
4. Uses Tweepy to find a certain number of tweets about that stock and uses TextBlob to determine if there is a positive or negative trends, using sentiment analysis.

### Requirements
* numpy
* scipy
* pyyaml
* tensorflow
* tweepy
* keras
* requests
* textblob

### TODO
- [x] Build neural network to classify past year's historical data
- [x] Perform sentiment analysis on collected Tweets
- [ ] Create portfolio-builder that allows for multiple stocks to be analyzed
- [ ] Build interactive webpage to display data and predictions 
