# Pharma-Sales

Specialization Project using Recurrent Neural Networks to predict future sales from an individual pharmacy, based on 8 grups of drugs.

Database: https://www.kaggle.com/milanzdravkovic/pharma-sales-data

# Folders Description
## EDA
Folder with Exploratory Data Analysis notebook.

## LSTMApproach
Folder with a notebook using LSTM neural network to predict one specific drug future sales.

## GRUApproach
Folder with a notebook using GRU neural network to predict one specific drug future sales.

## EsembleLearning
Folder with a notebook with the intention to use multiples RNN's  

# Notebooks Description

## EDA
Exploratory data analysis notebook, with the problem descriptiion (kaggle copy), plots to get a fully understend from the database and some insights.

## N02BE_Forecasting_LSTM
Nothebook using LSTM neural network to predict one specific drug future sales. Using one or more features, many kinds of feature engineering was implemented to try to improve generalization.

## N02BE_Forecasting_GRU
The same description of the last notebook can be used here, the only diffence is the implementention of a different kind of recurrent neural network (GRU)

## EsembleRNN
The idea here is to create a colaborative learning, using multiples recurrent neural network of differents types (LSTM and GRU) and times steps. This notebook it's not finish yet, so don't lose your time here.

# Future Improvements
There is still a lot of work to be done.

-  Finish the colaborative learning notebook, use the others files (saleshourly.csv, salesmonthly.csv, salesweekly.csv) as external features.
-  After performing well predicting a single drug, create a system that can predict all the drugs. 
