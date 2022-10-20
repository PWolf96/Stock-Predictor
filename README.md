# Stock-Predictor using LSTM

## Overview

This workbook will explore the possibility of analysing time-series data in the form of stock prices in order to predict future growth or decline. For this purpose, a Long-Short Term Memory (LSTM) methodology will be adopted. The methodology will use a user-defined set of consecutive days that will train a model to predict the following days' closing price. In order to do that, the model will be trained on readily provided data from **Yahoo finance api** in conjunction with additional features added to increase the model accuracy. Finally, different time-frames of look-backs will be compared to each other, in the attempt to find the most optimal solution.

For the purpose of this analysis, data for **Google** will be used imported using **Yahoo finance api**

## Libraries used
 - finta
 - pandas
 - numpy
 - matplotlib
 - seaborn
 - sklearn
 - keras

## Features

In this analysis the following techincal indicators were chosen:

 - High - the highest price for the day
 
 - Low - the lowest price for the day
 
 - Open - the price at which a stock has opened
 
 - Volume - the volume at which a stock has traded
 
 - Close - the price at which a stock has closed
 
 - Relative Strength Index (RSI) - Used as a momentum indicator commonly used to determine the strength of price changes in market. 

 - On Balance Volume - Used as a volume indicator, calculating the buying and selling pressures of a stock

 - Bollinger Bands -  Used as a volatility and trend indicator, plots three trend lines, determining whether a stock is overbought or oversold.
 
 ## How to use
 
  - Clone the repo
  
  - Run all cells
  
  ## Documentation 
  
  [Written report](Stock-Predictor/Stock-Predictor-LSTM.pdf)
