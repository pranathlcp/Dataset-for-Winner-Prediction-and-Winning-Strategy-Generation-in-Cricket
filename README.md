# In-game winner prediction and winning strategy generation in cricket: A machine learning approach

This repository contains the datasets used for the research study titled **In-game winner prediction and winning strategy generation in cricket: A machine learning approach**. 

## Authors
- Pranath Pussella
- Rajitha M Silva
- Chaminda Egodawatta

## Abstract

This study provides an in-game prediction of the winner for Twenty20 (T20) cricket by focusing on the matches played in the Indian Premier League. For the analysis, data were collected from 812 completed matches played between 2008 and 2020. Initially, several candidate features were identified, and then the LASSO method was applied as a feature selection technique to identify the most important set of features. Based on the identified important features, predictions are provided for each stage of a match where a T20 match can consist of a maximum of 240 stages. For each stage, three classification models were formed using Naive Bayes, Logistic Regression and Support Vector Machines. The prediction accuracy was used for evaluating the findings of the study, and the prediction accuracy of each model indicates the ratio between the number of correctly predicted instances and the total number of predicted instances. Naive Bayes demonstrated prediction accuracies ranging from 53.08% to 91.76% between the first and the 240th stage of matches, whereas the accuracy of Logistic Regression varied from 56.92% to 97.65%. In comparison, Support Vector Machines also displayed comparable outcomes with a prediction accuracy of 55.00% at the first stage, and 90.59% at the 240th stage. Furthermore, a strategy generator that assists the competing teams in the second innings to devise winning strategies, is presented in this study alongside an interactive web-based application for making in-game predictions, and for assisting the end users (players and coaching/managing staff) in decision making, based on the generated winning strategies.

## Where to find the published manuscript
The research manuscript can be found by visiting https://journals.sagepub.com/doi/abs/10.1177/17479541221119738

## Data Structure

The following table provides a summary of the data available in each file (dataset) inside this repository. 

|Dataset| Description |
|--|--|
| DatasetA.csv | A summary dataset containing match related information for 812 matches played in the Indian Premier League from 2008 to 2020 |
| TrainA.csv | The set of match data which is used for training purposes (created using DatasetA.csv with a split ratio of 0.70) |
| TestA.csv | The set of match data which is used for testing purposes (created using DatasetA.csv with a split ratio of 0.30) |
| DatasetB.csv | A ball-by-ball dataset corresponding to the matches in DatasetA.csv |
