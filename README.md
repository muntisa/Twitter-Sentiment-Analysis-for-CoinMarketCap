# Twitter Sentiment Analysis for CoinMarketCap
Twitter Sentiment Analysis for the top 10 cryptocurrencies on CoinMarketCap and the live sentiment analysis for a crypto

### Run the project (free online)

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/muntisa/Twitter-Sentiment-Analysis-for-CoinMarketCap/master)

### Description

There ar two scripts for twitter sentiment analysis:
1. Twitter sentiment analysis for top10 cryptos
Get the top 10 cryptocurrencies with Coinmarketcap APIs and analyse the user sentiments with Twitter APIs. Therefore, we have 2 stepts:
Notebook: [Twitter-Sentiment-Analysis-for-CoinMarketCap.ipynb](./Twitter-Sentiment-Analysis-for-CoinMarketCap.ipynb)
* Create a function to give you the list of Top10 cryptocurrencies from Coinmarketcap.
* Create a procedure to get and analyse the sentiment 15 tweets for a cryptocurrency.
* Use the above to analyse the sentiment for all Top10 cryptocurrencies.

2. Live sentiment analysis for a crypto
Notebook: [Live-Twitter-Sentiments-for-Cryptocurrencies.ipynb](Live-Twitter-Sentiments-for-Cryptocurrencies.ipynb)
* Input your Twitter API credentials, crypto keywords, number of tweets/connections, update interval
* run the notebook


### Acknowledgements

* [robertklim](https://github.com/robertklim) for the solution of the tweepy *async* error in Python 3.7: just [use python 3.6.6](https://github.com/tweepy/tweepy/issues/1017)! Or repace *async* variable with let's say *tr_async* in \Lib\site-packages\streaming.py (https://stackoverflow.com/questions/49339502/tweepy-on-macbook-pycharm-async-invalid-syntax).

Hf!

@muntisa
