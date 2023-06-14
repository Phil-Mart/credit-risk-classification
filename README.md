### credit-risk-classification
This model tests and validates credit risk for potential future loans using Supervised Learning techniques to ensure the highest accuracy. This process has important business implications as it relates to an increased profitability within the loan and interest segment of financial firms. 

# Step 1: Split the Data into Training and Testing Sets

* This code reads the data from the Resources folder into a Pandas DataFrame.
* From there I created the labels set "y" from the loan_status column and created the features "X" DataFrame from the remaining columns. 
* These values were used to split the data into training and testing datasets using train_test_split. 

# Step 2: Create a Logistic Regression Model

* I then fit a logistic regression model by using the training data (X_train and y_train).
* I saved the predictions on the testing data labels by using X_test and the fitted model.
* Afterwards, I evaluated the model's performance by generating a confusion matrix and classification report, as well as answering how well the logistic regression predicted the healthy and high-risk loan labels.

# Step 3: Write a Credit Risk Analysis Report

Attached you will find the analysis report, used to describe the specific findings to be shared with stakeholders. 
