# S&P500 Walk-Forward Modeling with Sklearn Pipelines

This notebook provides a framework for building and evaluating walk-forward models for the S&P500 index using Scikit-learn pipelines. 
The S&P500 is a widely recognized benchmark index for the US stock market, consisting of 500 of the largest publicly traded companies by market capitalization.

It's a useful starting point for building walk-forward models for the S&P 500 or other financial data.

## Table of contents
* [Feature Engineering] (#Feature)
* [Forecasting Methods] (#Forecasting)
* [S&P500 Historical Data](#S&P500)
* [Train-Test Split](#Train-Test)
* [Out-of-Sample Forecast](#Out-of-Sample)
* [Walk Forward Testing / Rolling Window Forecast](#Walk)

## Technologies
* Python version: 3.7

## Feature Engineering
The feature engineering process includes:
* Percent Change
* Difference of Change
* Daily Returns
* High-Low percent change
* Stoch RSI
* SMA
* Money Flow Index
* On Balace Volume (OBV)
Additionally, the notebook includes the ability to check for correlation between features and the target, as well as between features themselves.

## Forecasting Methods
* Out-of-Sample Forecast: a method of evaluating a model's performance by testing it on data that is not included in the training set 
* Walk Forward / Rolling Window Forecast: a technique used to simulate real-world trading scenarios, where the model is trained on historical data up to a certain point in time and then tested on new data that becomes available after that point, with the process repeated for each new data point.

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
