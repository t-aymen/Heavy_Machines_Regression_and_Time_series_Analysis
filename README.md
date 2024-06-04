# Heavy Machines Sales Regression and Time-series Analysis

## Context and Scope
The project involves predicting the auction sale prices of bulldozers using historical data from the Bluebook for Bulldozers competition on Kaggle. The dataset includes various features such as equipment types, usage, and configurations to build robust machine learning models.

The data is sourced from auction result postings, created and publically published by Fast Iron on Kaggle.

<b>About Fast Iron</b>

Fast Iron is a content-focused business that aids customers in creating enterprise data standards, cleansing data, and maintaining clean data. Utilizing proprietary applications and an ever growing data cleansing team, Fast Iron has normalized data for more than 2.5 million machine and customer records for the heavy equipment industry.

## Project Data

There are 3 main datasets:

* <ins>Train.csv</ins> is the training set, which contains data through the end of 2011.
* <ins>Valid.csv</ins> is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* <ins>Test.csv</ins> is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012.
For more information on this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/

## Evaluation
The evaluation metric for this competition is the <b>RMSLE</b> (root mean squared log error) between the actual and predicted auction prices.

## Features
A data dictionary provided by Kaggle detailing all features of the dataset can be found in the project files.
