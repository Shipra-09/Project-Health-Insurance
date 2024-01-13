# Cross-sell Vehicle Insurance Prediction
***

## Background Information :
An Insurance company that provide Health Insurance to its customers, usually they offer other insurance product to the customers through diffirent kind of marketing channel. In this case we will build a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.
***

## Problem Statement and Business Goals:
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.
***

## Methodology:

 1. Data copying and cleaning:
    * Import the training data
    * Recategorize data
    * check for null values and other informations
    * drop the duplicate values
 
 3. Exploratory Data Analysis:
    * Conduct all the necessary EDA using various graphs on the dataset
    * interpret the graphs
  
 4. Feature Engineering
    * check for outliers
    * correlation among the features
    * perform one hot encoding in case of categorical features
    * Feature selection
    * Data handelling
    * Applying Random over sampler since the data is imbalanced

 5. Model Building:
    * Splitting data into Training and Testing
    * Standardize the data using Standard scalar
    * Creating a base model of prediction
    * 3 different models ( Logistic Regression, KNN Classifier and Random Forest Clasifier)
   
 6. Model Validation:
    * Check the model diagonistics (accuracy, precision, confusion matrix) all the base model
    * Choose which model has the best accuracy score.

 7. Model testing on test data:
    * Import the test data
    * recategorize it according to the training data
    * predict it using above model

 8. Model output saving:
    * Save the predicted data with IDs
    * Save as excel file (Submission.csv)
***

## Conclusions:

       
