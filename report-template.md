# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of the Logistic Regression model was to predict whether or not a borrower was taking out a high or low risk loan by setting a predicting indicator, for this example a 0 was set for low risk loan and a q was set for a high risk loan.

* Explain what financial information the data was on, and what you needed to predict.

The data was extracted from a csv file by using multiple libraries such as: Numpy, sklearn to train the model, and Pathlib which was used to read in the csv file.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The model was trained to predict low and high risk loans. 

* Describe the stages of the machine learning process you went through as part of this analysis.

The first stage of my process was to seperate the data that I was using to predict from the data that was non-beneficial.The next step was to train the model to predict the low and high risk loans. 

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

The Logistic Regression Model was the only model that I used to complete this assignment due to the file using numerous numeric values. Using this model I was able to predict the risk level with extremely high accuracy.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Accuracy was 99%
    * Precision was 100%
    * Recall was 99% for low risk and 91% for high risk loans

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?

I only used the Logistic Regression Model which was able to have 100% on low risk loans with 99% accuracy to go along with it.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

For this model it is more important to predict the 0's instead of the 1's. If the model was to falsely predict a high risk loan then, the user would be protected from the other predictor.

If you do not recommend any of the models, please justify your reasoning.
