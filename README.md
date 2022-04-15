# stock prediction  ML models :

Just tried my hand around the stock market prediction using ML , Didn't use LSTM Models .                        Tried a different from scratch approach comprising of two different models
->1dtplain
->MACD_EMA

# 1dtPlain :
 
The most basic regression based time series stock predictor built from scratch on the NSE-NIFTY-50 Stocks conglomerate , The dataset [dataset : final_50_stocks.csv] included in the repository . Gives out pretty decent short term predictions but has an issue of high overfitting .

# MACD_EMA :
An improved version of the plain predictor improvises on a very important technical analysis factor to identify breakouts in the stock market being MACD: Moving average convergence divergence (MACD) is a trend-following momentum indicator that shows the relationship between two moving averages of a security's price and EMA :Exponential Moving Average is one other such basic fundamental trying to incorporate both of these to identify breakout worthy stocks to a 1% margin and getting a high level of accuracy for the daily traders . 
