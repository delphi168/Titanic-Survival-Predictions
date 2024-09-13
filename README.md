#Titanic Survival Prediction Model

This repository contains the implementation of a machine learning model that predicts the survival of passengers aboard the Titanic. The model is based on the famous Titanic dataset, which includes details about passengers such as their class, sex, age, family relationships, and more.

#Project Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. The objective of this project is to analyze the dataset and build a model that predicts whether a passenger survived the disaster based on features like:

Pclass: Socio-economic status (1st, 2nd, 3rd class)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Fare: Passenger fare
Embarked: Port of embarkation
Model Details
The model development includes the following steps:

Data exploration and visualization.
Handling missing values and feature engineering (e.g., extracting titles from names, encoding categorical variables).
Addressing class imbalance in the target variable (Survived).
Feature scaling and selection of the best features.
Model training using Random Forest Classifier.
Hyperparameter tuning to improve model accuracy.
Additionally, the project includes techniques for evaluating model performance, including the use of cross-validation and performance metrics like precision, recall, and the F1-score.
