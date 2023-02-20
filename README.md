# S&P500 Walk-Forward Modeling with Sklearn Pipelines

This notebook provides a framework for building and evaluating walk-forward models for the S&P500 index using Scikit-learn pipelines. 
The S&P500 is a widely recognized benchmark index for the US stock market, consisting of 500 of the largest publicly traded companies by market capitalization.

The model is trained on historical data and tested on out-of-sample data, allowing for a simulation of real-world trading scenarios. 
The feature engineering process includes daily returns, High-Low percent change, Stoch RSI, SMA, Money Flow Index, OBV, etc. Additionally, the notebook includes the ability to check for correlation between features and the target, as well as between features themselves.

The out-of-sample forecasting and walk-forward testing functionality allows for a rolling window forecast, which can help to evaluate the model's performance over time. This functionality can be particularly useful for evaluating models in dynamic market conditions, where the relationships between features and the target may change over time.

It's important to note that the results presented in this notebook should be taken with caution. While the models may show strong performance when predicting stock prices, these results are likely falsified due to the non-stationary nature of stock prices. To accurately compare different models and evaluate their performance, it is recommended to use stationary data such as daily returns or other normalized data.

Overall, this notebook provides a useful starting point for those interested in building walk-forward models for the S&P 500 or other financial data. The code is well-documented and includes detailed explanations of the various steps involved in the modeling process. Please feel free to fork the repository and adapt it to your own needs.

## Table of contents
* [S&P500 Historical Data](#S&P500)
* [Train-Test Split](#Train-Test)
* [Out-of-Sample Forecast](#Out-of-Sample)
* [Walk Forward Testing / Rolling Window Forecast](#Walk)

## Technologies
* Python version: 3.7

## S&P500 Historical Data
### Price Data
![](images/SP500%20Real%20Price.png)

## Train-Test Split
### Price Data
![](images/SP500%20Train%20Test.png)
### Daily Returns
![](images/SP500%20Daily%20Returns.png)

## Out-of-Sample Forecast
### Price Data
![](images/SP500%20Out-of-Sample%20Forecast%20Price.png)
### Daily Returns
![](images/SP500%20Out-of-Sample%20Forecast%20Raw.png)

## Walk Forward Testing / Rolling Window Forecast
### Price Data
![](images/SP500%20Walk-Forward%20Rorecast%20Price.png)
### Daily Returns
![](images/SP500%20Walk-Forward%20Forecast%20Raw.png)
