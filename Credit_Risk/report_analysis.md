# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to see if machine learning could accurately predict the credit risk of potential loans using the statistics of loans from previous clients. Statistics like, loan size, interest rate, income, debt, and whether or not the previous debtor defaulted, we created a supervised learning model to see if we could predict if someone was a credit risk.

The number of healthy and unhealthy loans were calculated by using the value counts method. Because of the large ratio imbalance between healthy loans and unhealthy loans (by approximately 30 times more), logistical regression was done on the data as is, and then done of the data after it was resized using a random oversampling model (which compensated for the extreme imbalance between the two targets).


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Precision:Out of all the loans that the model predicted would get default, 87% did. 
  * Recall:Out of all the loans that defaulted, the model predicted it 89% of the time.
  * Balanced Accuracy: The balanced accuracy is 94%



* Machine Learning Model 2:
  * Precision: Out of all the loans that the model predicted would default, 87% did.
  * Recall: Out of all the loans that defaulted, the model predicted it 100% of the time.
  * Balanced Accuracy:The balanced accuracy is 99.5%

## Summary

Of the two models, I would consider model 2.  The accuracy is better as it normalizes the data as to even out the values between the healthy loans and the unhealthy loans.  However, I would caution anyone in using this data as the near 100% accuracy is suspicious, and is indicative  of an overfit model whose data may not be as accurate as it is portrayed.
