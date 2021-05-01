# Bull-Dozer-ML-Model

To view the Jupyter notebook of this project -> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Hrushi11/Bull-Dozer-Machine-Learning-Model/HEAD)

Predicting the price of the bulldozers on previous data.

# 🚜 Predicting the sale Price of BullDozers using Machine Learning

To predict the sale price of Bulldozers.

## 1. Problem Definition

> How well can we predict the future sale price of a bulldozer, given its characteristic and previous examples of how much similar bulldozers have been sold for?

## 2. Data

The data is downloaded from the Kaggle Bluebook for bulldozers competition: <br>
https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set     throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 -   November 2012. Your score on the test set determines your final rank for the competition. 

## 3. Evaluation

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
For more on the evaluation on this project check: <br>
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

**Note:** The goal for most regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a Machnine Learning model which minimizes RMSLE.

## 4. Features 

Kaggle provides a data dictionary detailing all of the features of the dataset. 
