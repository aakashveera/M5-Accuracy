# M5-Accuracy

This repo consists the solution for the competition kaggle M5-Accuracy. Competition Link -> https://www.kaggle.com/c/m5-forecasting-accuracy/. It is a time series forecasting competition and the goal of the competition is to predict the sales for the next 28 days.

## Data Description

The dataset from the kaggle competition is used (https://www.kaggle.com/c/m5-forecasting-accuracy/data) and comes with the sales history of 10 stores from three states CA,TX,WI from Jan 2011 to June 2016. The product in the training set belongs to three categories HOBBIES, FOODS and HOUSEHOLDS.

## Evaluation Metric

Weighted Root mean squared Error is used as the evaluation metric for the competition and <b>LightGBM</b> is used in the above solution and <b>0.62128</b> on private leaderboard and <b>0.22445</b> public leaderboard is obtained
