# credit-risk-classification
This model tests and validates credit risk for potential future loans using Supervised Learning techniques to ensure the highest accuracy. This process has important business implications as it relates to an increased profitability within the loan and interest segment of financial firms. 

## Step 1: Split the Data into Training and Testing Sets

* This code reads the data from the Resources folder into a Pandas DataFrame.
* From there I created the labels set "y" from the loan_status column and created the features "X" DataFrame from the remaining columns. 
* These values were used to split the data into training and testing datasets using train_test_split. 

![Screen Shot 2023-09-16 at 9 40 43 PM](https://github.com/Phil-Mart/credit-risk-classification/assets/120279988/b6e6b6c6-3af4-48ec-b10a-7aeb8d4e8ccb)

## Step 2: Create a Logistic Regression Model

* I then fit a logistic regression model by using the training data (X_train and y_train).
* I saved the predictions on the testing data labels by using X_test and the fitted model.
* Afterwards, I evaluated the model's performance by generating a confusion matrix and classification report, as well as answering how well the logistic regression predicted the healthy and high-risk loan labels.

![Screen Shot 2023-09-16 at 9 41 58 PM](https://github.com/Phil-Mart/credit-risk-classification/assets/120279988/9277b364-e4db-49f9-bff4-ce3145c6fb88)


## Step 3: Write a Credit Risk Analysis Report

## Credit Risk: Supervised Model Report 

## Overview of the Analysis

* Purpose of the analysis: to predict the probablity of high-risk applicants in order to reduce total number of defaults on bank loans.
* Financial information used:  We used the following categories of historical loan data to train our model in order to see if it could predict correctly the outcome of the loan: 
  Loan size
  Interest rate
  Borrower income
  Debt-to-income
  Number of accounts they had
  Deragatory remarks
  Total debt, and 
  Loan status (the outcome)

* In order to test the model, separated all observable data with its results, which made the outcome data separate from the machine learning process. This made it easy to verify and calculate the model's results. 
* Out of the 77036 loans, 2500 of them defaulted, making it a small and important percentage of the total loan count.
* Synopsis of analysis:
  We split the data into 4 categories: 2 training sets, 2 testing sets
  We created a logistic regression model , fit it to training data, and had it make predictions
  We  compared its predictions to the list of actual outcomes
  Analyzed the results 

## Results

* Balance Accuracy Score: 95.2%. This model works very strongly to predict loan outcomes. 
* Precision: Model predicted with 100% accuracy low-risk loans, 85% high-risk loans (substantial improvement).
* Recall: both risk level metrics above 90%: high-risk @91%, low-risk @99%


## Summary

* This model currently works better than the industry stanard, given this number of samples and data points. 
* Discerning potential high-risk loan holders is of most importance, because those accounts are responsible for the majority of the bank's lost earning potential. This single category, when managed correctly, can increase the institution's bottom line by over 1000 basis points. 

The Linear Regression model should be implemented immediately to help assist associates give properly profitable loans to potential customers. 


# [Linkedin Profile](linkedin.com/in/phil-mart) 
# Email: [Phillip Martinez](PhillipMartinez@my.unt.edu) 

