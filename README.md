# Experimenting-with-machine-learning-in-R-with-tidymodels-and-the-Kaggle-Titanic-dataset

## Introduction
This repository contains an end-to-end analysis and solution to the Kaggle Titanic survival prediction competition. I have structured this notebook in such a way that it is beginner-friendly by avoiding excessive technical jargon as well as explaining in detail each step of my analysis. This notebook also includes brief explanations of some basic data science concepts and terminology.

## Problem statement
Given what we know about a passenger aboard the Titanic, can we predict whether or not this passenger has "survived"? In other words, we are training a Machine Learning model to learn the relationship between passenger features and their survival outcome and susbsequently make survival predictions on passenger data that our model has not been trained on.

This is a binary classfication problem in machine learning as we are classifying the outcomes of passengers as either survived or did not survive the Titanic.

## Evaluation metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by our model. This is known as accuracy.

## Data description
Below are the description of the features in the data:

- Survival: 0 = Did not survive, 1 = Survived
- Pclass: Ticket class where 1 = First class, 2 = Second class, 3 = Third class. This can also be seen as a proxy for socio-economic status.
- Sex: Male or female
- Age: Age in years, fractional if less than 1
- SibSp: Number of siblings or spouses aboard the titanic
- Parch: Number of parents or children aboard the titanic
- Ticket: Passenger ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Point of embarkation where C = Cherbourg, Q = Queenstown, S = Southampton
- Medium article
- Link to full project write-up on Towards Data Science here.

## References
https://www.kaggle.com/competitions/titanic
https://www.rebeccabarter.com/blog/2020-03-25_machine_learning/

