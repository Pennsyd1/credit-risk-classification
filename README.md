# credit-risk-classification
# Module 12 Report Template

## Overview of the Analysis

The purpose of the analyis is to create a model that predicts the likelyhood of loans beinf healthy or high risk based on various variables.  The variables used to create this model is loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. Thd data used had 75036 records of healthy loans and 2500 records of high risk loans. First I split the data into training and testing sets using train_test_split, with a random state of 1. Then I Initiate a logistic regression model using LogisticRegression and fit the model to the training data. Next I make predictions on the testing data using predict and calculate and print the accuracy score of the model using accuracy_score. Lastly, I generate a confusion matrix to evaluate the model's performance using confusion_matrix. Finally I used the RandomOverSampler module from the imbalanced-learn library to resample the data.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy: 99.10%
  *Precision: 100% for healthy loans, 85% for high risk loans
  *Recall scores: 99.0% for healthy loans, 91% for high risk loans



* Machine Learning Model 2:
  * Description of Model 1 Accuracy: 99.38%
  *Precision: 100% for healthy loans, 84% for high risk loans
  *Recall scores: 99.0% for healthy loans, 99% for high risk loans

## Summary


    I would not recommend either models because both models feature lower accuracy for predicting high risk loans which is what is most implortant when looking at credit risk. The accuracy level is higher for healthy loans so it could be more reliable in predicting that. If more samples of high risk loans are added I believe it will even out and increase the accuracy to improve this model.

