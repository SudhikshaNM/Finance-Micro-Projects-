# Finance-Micro-Projects-
A collection of Python-based finance micro-projects exploring stock analytics, sentiment analysis, and quantitative models.

For now, this repo contains 4 quantitative mini-projects demonstrating signal extraction, anomaly detection, and portfolio analytics.

Projects:
1. News Sentiment vs Next-Day Stock Return
2. Price-Volume Divergence Detector
3. Correlation Heatmap Across Global Assets
4. Simple ML Next-Day Return Predictor

All notebooks are Python-based, reproducible, and designed to understand and learn quantitative thinking and financial intuition.

1.News Sentiment vs Next-Day Stock Return:
>Pulls recent stock news headlines and calculates sentiment using VADER.
>Compares average sentiment against next-day stock returns to explore correlations.
>Provides a scatter plot visualization showing potential alignment of positive/negative sentiment with returns.
>Highlights “sentiment surprises” as insight into unexpected market moves.

2.Price-Volume Divergence Detector:
>Uses historical stock data to compute daily price and volume changes.
>Detects anomalous days where volume spikes but price remains flat.
>Plots price series with highlighted events, providing a visual anomaly detector.
>Helps understand potential precursors to market volatility or signal opportunities.

3.Correlation Heatmap Across Asset Classes:
>Downloads daily prices for multiple assets: S&P 500, Nasdaq, Gold, Crude Oil, Bitcoin, Bonds.
>Computes daily returns and generates a correlation matrix with a heatmap.
>Highlights strong and weak correlations between assets.
>Provides insight into portfolio diversification and market regime shifts.

4.Simple ML Next-Day Return Predictor (Baseline):
>Generates lagged return features from stock price data.
>Trains a logistic regression model to predict if next-day return will be positive or negative.
>Outputs accuracy and confusion matrix for evaluation.
>Demonstrates ML applied to financial time series and explains the challenge of noisy market data.
