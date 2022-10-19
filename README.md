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
