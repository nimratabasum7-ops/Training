# Training
Titanic Dataset - Logistic Regression Analysis

This project analyzes the Titanic passenger dataset to predict survival outcomes using Logistic Regression. The dataset is provided as an Excel file and contains passenger information such as age, gender, class, and fare paid.

Dataset Description

The Titanic dataset includes the following key features:

PassengerId: Unique identifier for each passenger

Survived: Survival status (0 = No, 1 = Yes) — target variable

Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)

Name: Passenger name

Sex: Gender of the passenger

Age: Age in years

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number (often missing)

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Objective

The goal is to build and evaluate a Logistic Regression model to classify whether a passenger survived or not, based on available features.

Methodology

Load and preprocess the Excel data in Jupyter Notebook

Handle missing values and encode categorical variables

Split the dataset into training and testing sets

Train a logistic regression model on training data

Evaluate the model using accuracy, confusion matrix, and classification report
