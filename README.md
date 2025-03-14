# Credit-risk-classification

# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
  - The purpose of this challenge is to use various techiques to train and evauate what the loan risk are. Data that was consideered was income, the number of account available, and debts were used to evaluate the loan status. We used Machine Learning process to be able to to determine and establish an X and Y varible, as well as splitting up the data into training and testing so the results can be analyzed.
    In this challenge we imported LogisticRegression to instantiate a model to assign a random_ state. Then a prediction was made using the testing data, then reviewied was the dataframe output was to genarate a confusion matrix.
     

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
 Confusion Matrix:
True Positive: 18658
False Positive: 37
False Negative: 107
True Negative: 582

Classification Report:

Precision:
Healthy: 1.00
High-Risk Loan: 0.84

Recall:
Healthy: 0.99
High-Risk Loan: 0.94

F1-score:
Healthy: 1.00
High-Risk Loan: 0.89

Accuracy: 0.99

Macro Avg-
Precision 0.92 
Recall 0.97
F1-score0.94

Weighted Avg: 0.99 (Precision), 0.99 (Recall), 0.99 (F1-score)

## Summary

The model exhibits outstanding performance, achieving an overall accuracy of 99%. The precision and recall scores indicate that it effectively identifies healthy loans while maintaining strong capability in detecting high-risk loans. Given the importance of correctly identifying high-risk loans over the occasional misclassification of a healthy loan, the model appears well-suited for this task. Therefore, it is recommended for deployment, with the understanding that continuous monitoring and potential refinements may be necessary to further minimize false negatives without compromising overall effectiveness.
