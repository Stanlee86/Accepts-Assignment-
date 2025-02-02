Logistic Regression Model for Predicting Accepts Assignment among medical suppliers

Introduction
This project examines whether medical equipment suppliers accept assignment, that is, consent to receive direct payment from Medicare at a set rate. Policymakers and service providers can improve their offerings by knowing the elements that affect this acceptability. This research uses Medical equipment suppliers data which is a list of Suppliers that indicates the supplies carried at that location and the supplier's Medicare participation status  to predict supplier assignment acceptance. The project uses logistic regression model to understand key factors influencing assignment acceptance and provides insights into supplier behaviours.


Libraries Used

The project is implemented in Python using the following key libraries:

matplotlib - used for visualization

pandas - used for data manipulation

scikit-learn - used for logistic regression modelling

Repository Structure

The repository contains the following files:

C:\Users\obias\blog project.ipynb - Python script for project

C:\Users\obias\README.md - README  documentation for project

C:\Users\obias\Medical-Equipment-Suppliers.csv - dataset used for project


Project structure

Loads the dataset

Visualize outcome variable

Pre-process categorical and numerical variables using pd.get_dummies() and StandardScaler

Splits the dataset into training and testing sets

Trains a logistic regression model using scikit-learn

Evaluates the model and prints performance metrics



Results Summary

The trained logistic regression model achieved:

Accuracy: 85%

Precision: 86%

Recall: 87%

ROC AUC Score: 92%

These metrics indicate that the model performs well in distinguishing between suppliers who accept assignments and those who do not.

