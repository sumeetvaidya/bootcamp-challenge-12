# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose of the analysis is to determine credit risk of the loan i.e. whether the loan is healthy or risky. 
* Explain what financial information the data was on, and what you needed to predict.
    The data includes :
    * loan size
    * interest rate	of the loan
    * borrower income	
    * debt to income ratio
    * num of accounts	
    * derogatory marks	
    * total debt
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
 The basic information includes value counts to determine how many loans were healthy and how many were risky.
* Describe the stages of the machine learning process you went through as part of this analysis.
    The stages of the machine learning process are
    * Prepare the Data
    * Split the Data into Train and Test partitions
    * Choose the model
    * Fit the Model to the training data (Train the model)
    * Run prediction on the test data
    * Compute Accuracy, Confusion Matrix, Precision and Recall numbers
    * Evaluate the model based on the statistics in the previous step.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    The models used is LogisticRegression. There is RandomOverSampler method used in the second model.
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy of the Model =99%, Precision= 85%, Recall = 91%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy of the Model =99%, Precision= 84%, Recall = 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
The Model 2 performs better in the Recall category. The Recall category is important becauase it shows better results for risky loans (1s)
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Model 2 is better in predicting risky loans (1s)

* If you do not recommend any of the models, please justify your reasoning.
    Model 2 is preferred for predicting risky loans 

