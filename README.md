# trading_ml
Data acquisition, data visualization, data manipulation, applied simple classifiers machine learning to predict buy/sell/hold

0. visualized the stock price trend using candlestick and trading volumn
1. Used beautifulsoup and request packages to acquire all tickers in s&p500 and saved to local
2. looped all tickers to yahoo API(Pandas.DataReader) to get each HLOC data
3. manipulated the data frame (set_index, drop, rename column, join data frame)
4. visualized the correlation of every stock in s&p 500 using heatmap
5. came up easy trading strategy. If the stock rises 3% in next 7 days, buy it now. If the stock decreases 3% in next 7 days, sell it now. Otherwise hold it.
6. applied cross_validation and VotingClassifer to split, train and test the data.
