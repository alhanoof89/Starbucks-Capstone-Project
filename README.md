# Starbucks-Capstone-Project
This is a Capstone Project Submitted to Udacity

This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.


# Motivation

This project is the Capstone Project of Data Science Nanodegree Provided by Udacity. 

# Libraries

import pandas as pd

import numpy as np

import math

import json

from datetime import datetime

from time import time

import matplotlib.pyplot as plt

import seaborn as sns

import warnings

from sklearn.naive_bayes import GaussianNB

from sklearn.ensemble import AdaBoostClassifier

from sklearn.metrics import accuracy_score,f1_score

from sklearn.model_selection import train_test_split,GridSearchCV

from sklearn.naive_bayes import GaussianNB

from sklearn.neighbors import KNeighborsClassifier

from sklearn.svm import SVC

# Summary of the results
1- who are responsive to coffee offers?
we have found that the males are more responsive to coffee offers. and customers on age range 50–65 this answer is proven with charts above

2- how can income affects number of responsive customers to the offers?
obviously, the data showed that male are more responsive to the offers. and when we tried to analyse the data more, we found that male customers have a higher income than females which justify why the number of males consuming offers is higher than females

3- which offer is preferred to customers based on age/gender/income?
Males are responding more to the discount offer, but both males and females have a high response to BOGO offer and almost has the equal number of responses from both males and females. Starbucks should consider this when offering & promoting an offer (Highest response of males)

4- Knowing all above, we need to predict the future offer which will attract more customers

after analysing all the data above and applying ML models on the cleaned data sets, we decided to use AdaBoostClassifier model on predicting the preferred offer and which is more attractive to the customer to buy and the result was BOGO

# Files 

The code is available here on github on file : Starbucks_Capstone_notebook.ipynb
The HTML file of the code: Starbucks_Capstone_notebook.html

# Findings

all the findings are on the below plog post link on Medium:
https://medium.com/@alhanoof.alsharyan/starbucks-capstone-project-5c6b56cd7450


