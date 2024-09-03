# Titanic Dataset EDA 

This project involves an exploratory data analysis (EDA) of the Titanic dataset, which is one of the most well-known datasets for data science and machine learning. The analysis aims to uncover patterns in the data and draw insights that might have affected the survival rates of the passengers.
Link for the dataset :- https://www.kaggle.com/datasets/brendan45774/test-file

## Introduction
The Titanic dataset provides information on the passengers aboard the Titanic ship, including their age, sex, passenger class, and whether they survived the shipwreck. This project performs a detailed analysis to understand the factors that contributed to the survival of passengers.

## Dataset
The dataset used in this project is the Titanic dataset, which can be found on Kaggle or other open data sources. The dataset includes various features such as:

* PassengerId: Unique ID for each passenger
* Survived: Survival indicator (0 = No, 1 = Yes)
* Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
* Name: Passenger's name
* Sex: Passenger's gender
* Age: Passenger's age
* SibSp: Number of siblings/spouses aboard
* Parch: Number of parents/children aboard
* Ticket: Ticket number
* Fare: Fare paid for the ticket
* Cabin: Cabin number
* Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

  ## Libraries Used
  command :
      import pandas as pd
      import numpy as np
      import seaborn as sns
      import matplotlib.pyplot as plt
      import warnings
      from scipy.stats import ttest_ind, chi2_contingency
      warnings.filterwarnings('ignore')
