# CreditCard-Fraud-Detector
## Summary:
Credit card fraud happens when someone — a fraudster or a thief — uses your stolen credit card or the information from that card to make unauthorized purchases in your name or take out cash advances using your account.
 Our team decided how machine learning will predict the fraud Transactions. We search the data in Kaggle we got the simulated credit card fraud transactions csv. we Brain stormed and come up with some solution. Please visit our application what we have predicted using supervised learning.

## Overview of development steps:
* Original fraudtrain.csv has 1297868 rows and 23 columns. We cleaned the data replaced the nan values with zeros.
* Used one hot encoding to convert the string to numeric data in the selected columns.
* By using Random Forest classifier we selected the feature importance to narrow down our features to the model and split the data and    scaled then trained the logistic regression model with the trained data. Once the model is fitted then we predicted outcome using test data.

##Data source:
[Kaggle] https://www.kaggle.com/kartik2112/fraud-detection?select=fraudTrain.csv
         https://www.kaggle.com/kartik2112/fraud-detection?select=fraudTest.csv

## Visualizations:
* The Cleaned csv file is uploaded into the Tableau Desktop.
* The following visualizations were made based on the factors affecting the amount ,category, Transactions, age, locations.
* used plotly made confusion matrix and correlation diagrams.

### Machine learning models used:
* Logistic Regression
* Gaussian  naive bayes
* K-nearest neighbor(KNN )
* Supprot Vector machine(Svm)

## Tools used in this project:
* Python: Pandas, Flask, SKlearn
* Webpage Design: HTML, Css , Bootstrap
* Tableau
* PostgreSQL 

## Usage
## Local
* Make sure all the requirements from requirements.txt are up to date
* Run app.py
* Acess at local host: http://127.0.0.1:5000/

### Remote Access
* [Heroku] (Placeholder)



        


