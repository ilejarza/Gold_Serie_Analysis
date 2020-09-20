# Time Series Regression - Gold Value Prediction

### Authors: @Íñigo Lejarza @Cesar S. @Stanley Salvatierra @ketcx @Fernando T @susyjam

## Summary
The objective of this project is to create a model that will help in predicting future market values of Gold, using the resources learnt in the Azure Machine Learning Scholarship.

## Introduction
This project will require a model capable of predicting values for future times. Because of that the required model will be a Regressor, which will be trained with previous values of the serie.

## Data Collection
For our project we found a complete dataset with Gold Prices in the web site of World Web Council (https://www.gold.org/).
The information available in that site includes price of Gold in many currencies, and the values per day, per month, and per year.

## Dataset Preparation
In our project we took a subset of the dataset available.
We worked with the Daily Time Series of Gold in U.S. dollars (USD) from 2017 to 2020.
That dataset was normalized using a MinMaxScaler() from sklearn.preprocessing. 

## Model Selection
After testing many different approachs, we obtained the best approach by using a Long-Short Temr Mempory Neural Network.

## Train/Test Data Splitting
For this project we splitted the Dataset with the following criteria:  
Train Data: 2017-01-02 to 2020-04-16  [859 points]  
Test Data:  2020-04-16 to 2020-08-28  [ 96 points]  

