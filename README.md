# CAPSTONE PROJECT

## Introduction

Starbucks sends to their users offers through the Starbucks reward app.  This offer could be a discount or a BOGO (buy one get one free). These promotions aren’t displayed to each user at the same time so the goal is to determine which group responds best to which offer type.


There are two proposals of problems to solve in this challenge. One of the problems to be solved is to predict if a customer will respond to an offer. Since each offer given to the client means a cost to the company it’s important to be efficient sending these offers. 


Another problem to solve, for those customers who have completed an offer, is to determine which variables are correlated with increasing the amount of transaction, given an offer difficulty, ie, since a customer spent 40 and the difficulty was 10, determine if there is some variable correlated with these extra spending. 


## Notebooks

The following notebooks were build to solve this problem:

* Data Exploration.ipynb - Data exploration, merging datasets, some functions to creating the offer completed status.
* Data Processing.ipynb - Spliting dataset in training and testing, binning variables, among others.
* Modeling.ipynb - Three differents model were built with Scikit Learn.


## Dataset

The starting datas were provieded by Starbucks in json format: 

* portfolio.json
* profile.json
* transcript.json

In each step of the notebook new dataset are created:


## Libraries

The perject were developed in Python 3.6 and the following libraries were used:

* pandas==1.1.3
* numpy==1.19.2
* math==1.1.0
* json==4.0.1
* matplotlib==3.3.2
* sklearn==0.23.2
* optbinning==0.9.2

## Documents

You can find the explanation of this project with the conclusions and references in the file: **Capstone Project.pdf**