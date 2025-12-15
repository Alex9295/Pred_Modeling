# Titanic Survival Prediction - Machine Learning Project

## 🎯 Overview
This project implements a machine learning pipeline to predict whether a passenger survived the Titanic disaster based on their characteristics:
Exploratory Data Analysis (EDA) to understand patterns and relationships

Data Preprocessing including missing value imputation, outlier removal, and feature scaling

Multiple Model Training with Logistic Regression, Decision Trees, Random Forest, and SVM

Hyperparameter Tuning using GridSearchCV and RandomizedSearchCV

Model Evaluation with accuracy, precision, recall, and F1-score

Feature Importance Analysis to understand model decisions

Model Serialization for deployment

## 📊 Dataset
The Titanic dataset contains information about 891 passengers with the following features:

Feature	Description	Type	Notes
PassengerId	Unique ID for each passenger	Integer	Index
Survived	Survival (0 = No, 1 = Yes)	Integer	Target Variable
Pclass	Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)	Integer	Socioeconomic status
Name	Passenger name	String	Contains titles
Sex	Gender	String	Binary categorical
Age	Age in years	Float	177 missing values
SibSp	# of siblings/spouses aboard	Integer	Family size component
Parch	# of parents/children aboard	Integer	Family size component
Ticket	Ticket number	String	Alphanumeric
Fare	Passenger fare	Float	Ticket price
Cabin	Cabin number	String	687 missing values
Embarked	Port of embarkation	String	C=Cherbourg, Q=Queenstown, S=Southampton
Dataset Statistics:

Total passengers: 891

Survived: 342 (38.4%)

Died: 549 (61.6%)

Missing values: Age (19.9%), Cabin (77.1%), Embarked (0.2%)
