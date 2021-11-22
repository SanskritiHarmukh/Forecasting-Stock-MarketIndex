# **Forecasting-Stock-Market-Index**



## Motivation and Purpose of the project

As we know Stock Market prices are highly unpredictable and volatile. This means that there are no consistent patterns in the data that allow one to model stock prices over time near-perfectly. So, as a stock buyer you can reasonably decide when to buy stocks and when to sell them to make a profit. Instead of considering it a stochatic or random process and that there is no hope for machine learning. We are trying to model the data, so that the predictions one make correlate with the actual behavior of the data.This is where time series modelling comes in. You need good machine learning models that can look at the history of a sequence of data and correctly predict what the future elements of the sequence are going to be.

## What does the project use?
We are working with Time Series Model, which analyzes a sequence of data points collected over a time interval. In time series analysis, analysts record data points at consistent intervals over a set period of time rather than just recording the data points intermittently or randomly. Time series data can be used for forecasting—predicting future data based on historical data.

## We are using 3 major open-source frameworks and tools in our project.

# Streamlit: The fastest way to build and share data apps


Streamlit :- Streamlit is an open-source python framework for building web apps for Machine Learning and Data Science. We can develop and deploy our web app using Streamlit very easily. In just a few minutes you can build and deploy powerful data apps. 



# Prophet: Automatic Forecasting Procedure

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.

# Yahoo Finance: To get free stock quotes 
Yahoo! Finance is a media property that is part of the Yahoo! network. It provides financial news, data and commentary including stock quotes, press releases, financial reports, and original content. It also offers some online tools for personal finance management.

## Python Installation 

**1.** Make sure you have python installed in your system already. If not, you can install it using in following command your terminal for installation
```
sudo apt install python:latest 
```
 **2.** check version using 
 ```
 python3 --version
 ```
**3.**. Now, for installing and managing the software packages, we'll first install pip using 
```
sudo apt install python3.8 
```
and can check version by
```
pip3 --version
```
**4.** Next thing to do is create a virtual environment to separate your site packages used in this project from your rest of the projects, therefore to install use,
```
pip install virtualenv
```
create using virtualenv <your_env_name> and activate using source <your_env_name>/bin/activate.


