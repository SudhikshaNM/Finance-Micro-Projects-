A collection of Python-based finance micro-projects exploring stock analytics, sentiment analysis, and quantitative models. These notebooks demonstrate signal extraction, anomaly detection, and portfolio analytics in a reproducible, research-focused way.

Projects
1. News Sentiment vs Next-Day Stock Return
->Pulls recent stock news headlines and calculates sentiment using VADER.
->Compares average sentiment against next-day stock returns to explore correlations.
->Visualizes the relationship using scatter plots, highlighting alignment of positive/negative sentiment with returns.
->Shows “sentiment surprises” as insights into unexpected market moves.

2. Price-Volume Divergence Detector
->Computes daily price and volume changes from historical stock data.
->Detects anomalous days where volume spikes but price remains flat.
->Plots price series with highlighted events, acting as a visual anomaly detector.
->Helps identify potential precursors to market volatility or signal opportunities.

3. Correlation Heatmap Across Asset Classes
->Downloads daily prices for multiple assets: S&P 500, Nasdaq, Gold, Crude Oil, Bitcoin, Bonds.
->Computes daily returns and generates a correlation matrix with a heatmap.
->Highlights strong and weak correlations between assets.
->Provides insights into portfolio diversification and market regime shifts.

4. Simple ML Next-Day Return Predictor (Baseline)
->Generates lagged return features from stock price data.
->Trains a logistic regression model to predict if the next-day return will be positive or negative.
->Outputs accuracy and confusion matrix for evaluation.
->Demonstrates ML on financial time series and explains the challenge of noisy market data.
