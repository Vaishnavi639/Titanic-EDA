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

  
      import pandas as pd
      import numpy as np
      import seaborn as sns
      import matplotlib.pyplot as plt
      import warnings
      from scipy.stats import ttest_ind, chi2_contingency
      warnings.filterwarnings('ignore')


## Data Cleaning
Basic data cleaning steps were performed, including:

* Handling missing values
* Converting data types where necessary
* Removing unnecessary columns

### Key functions used:

* shape()
* describe()

## Exploratory Data Analysis (EDA)

** 1. Basic Information **
* Checked the shape and summary statistics of the data.
* Analyzed the distribution of numerical and categorical features.
  
** 2. Visualizations **
* Countplot of Gender: Visualized the distribution of male and female passengers.
* Countplot of Passenger Class: Analyzed the distribution of passengers across different classes.
* Countplot of Embarked: Analyzed the distribution according to Embarked.
* Violin Plot of Age, Sex, and Survival: Explored the distribution of ages by gender and survival status.
* Line Chart: Showed trends over continuous variables.
* Histogram (Histplot): Examined the frequency distribution of continuous variables.
* Heatmap: Visualized the correlation matrix to understand relationships between features.

** 3. Correlation Analysis **
* Identified correlations between features using a heatmap.
  
** 4. Statistical Tests **
* T-Test: Performed t-tests to compare means between groups (e.g., survival by gender).
* Chi-Square Test: Tested for independence between categorical variables (e.g., survival by passenger class).

## Conclusion:

The analysis provided insights into the factors that influenced survival on the Titanic. For example, gender, age, and passenger class were significant factors.


