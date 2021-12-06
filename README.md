# Credit Card Fraud Detection Web App
![Images](https://cdn.dnaindia.com/sites/default/files/styles/full/public/2017/04/04/562375-cyberfraud-040417.jpg)


This repository contains the procedure we followed to deploy our web app of Credit Card Fraud detection on Heroku.

Since the data for credit card fraud is not available in real form(due to confidentiality), and is availbale only in dimensionality reduced form, we will be sharing some of the test cases here.

## Specification about what we used and achieved.

***************

### Model Training

- Architecture
    - Logistic Regression with balanced class weight.

- Inference Results
    - Accuracy: 0.976
    - Recall: 0.896

***************

### Web App Production

- Procfile
    - Contains the type of app.
- Requirements
    - Libraries needed to run the app.
- Templates
    - Files required for rendering purpose
- Static
    - CSS styles
- App
    - Main file which will run our Web App.

***************

## Report

A thorough report on what we did can be found in *_FinalReport.md_* or *_FinalReport.pdf_* file.

****

## Test Data for Fraud Transaction:

Testing data for fraud transaction can be found in the ***"fraud_values.csv"*** file. 

***************

## Test Data for Valid Transaction:

Testing data for a Valid transaction can be found in the ***"valid_values.csv"*** file.


Developed by:
Aman Gupta 
Srilikhith Sajja 
Kishu Jain 
Tanmay Chaturvedi