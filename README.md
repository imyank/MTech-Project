# MTech-Project

This Thesis work is based on Prediction of Financial Stock price prediction using Deep learning techniques

## Overview

We propose an ensemble model of CNN-BiLSTM and a modified Trans-
former (incorporating temporal effect of stocks) which will be predicting stock prices of
two IT companies: Amazon and Facebook. Performance metric taken are Root Mean
Square Error(RMSE) and Mean Absolute Error (MAE). We have done analysis on en-
semble CNN-BiLSTM and on Transformer model. The performance has been analysed
by finding the RMSE and MAE scores for each of the above models and concluded that
minimum score in both the metric has been obtained in Transformer model.

## Dataset

The data has been down- loaded using yfinance library. This library directly downloads data from yahoo finance. The data is taken from August 2014 to December 2021 on daily basis. For both the proposed models, train set taken is from August 2014 to February 2020 while the test set is the remaining year. There are total 1858 data points

## Architecture

A stock price follows some periodic patterns so it is important to cover the temporal effect for prediction. Time2vector concept has been leveraged to provide this effect with Transformer model. The time is divided in two parts: periodic and non-perodic(or linear component).

## Findings

Since the stock prices are not standardized so the errors are not in range 0-1

[![Screenshot-2022-09-13-at-9-55-44-PM.png](https://i.postimg.cc/2yH9tj62/Screenshot-2022-09-13-at-9-55-44-PM.png)](https://postimg.cc/8f6bJSL6)



## For more details check out the thesis report and code
