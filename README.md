# credit-risk-classification

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of this analysis is to determine the loan risk based on the creditworthiness of a borrow.

* Explain what financial information the data was on, and what you needed to predict.

The financial data was from historical data which included, 
loan_size,interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt,loan_status.



* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

I was trying to predict based off the historical data how can I determine whether the loan is healthy or too risky to approve by using testing predictions. 

loan_status
0    75036
1     2500



* Describe the stages of the machine learning process you went through as part of this analysis.

Pre-processing data. Split the dataframe where y = loan status and x = the remaining information from the dataframe. 


* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

I used logistic regression that modeled the data into two groups healthy loan and high-risk loan. Which is the better method as the the data can only be split into two groups. (healthy/high-risk)




Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    Accuracy: 0.99
    Precision:
        '0' : 1.00
        '1' : 0.85
    Recall:
        '0' : 0.99
        '1' : 0.91

       
       

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The model performed well with an overall accuracy of 99%.
However that is because it predicted better for healthy loans.
In this case the performance definatley depends on the problem.
Prediciting high-risk loans correctly would be more critical than correctly identifying healthy loans. If the model misclassified more high risk loans as healthy loans that will lead to a significant risk to financial losses. 
