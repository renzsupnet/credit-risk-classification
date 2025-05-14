# Module 12 Report

## Overview of the Analysis


1. ### Purpose
        To be able to define a logistic regression model and classify a loan as high-risk or safe using financial data from a csv.

2. ### Data
        Data is imported from a csv containing loan_size, interest_rate, borrower_income,debt_to_income, num_of_accounts, derogatory_marks, total_debt, and loan_status.

3. ### Prediction Target
        The regression model's prediction target is the loan_status where 0 is a safe loan and 1 is a high-risk loan.

4. ### Machine Learning Process
        First, import data into a DataFrame. Split the DataFrame into a Label(X) df and a Target(y) df. Split data into a training dataset and a testing dataset. Define a logistic regression model using a random_state of 1. Fit the model with training data. Use the model to make predictions using testing data.

## Results


* Logistic Regression Model:
    * The logical regression model scored excellently when it comes to precision. It has a macro_avg of 0.94 and a weighted_avg of 0.99 a near perfect score. 
    * The model also scored excellently when it comes to recall.
    It has a macro_avg of 0.97 and a weighted_avg of 0.99.

## Summary

    In conclusion, the logistic regression model made excellent predictions when it comes to classifying loans into 0(safe loans) and 1(high-risk loans). With a weighted_avg score of 0.99 precision, the model can be used by banks. From a bank's perspective it is better to accurately predict high-risk loans to protect its capital in the case of non-payment.
