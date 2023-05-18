
# Credit-risk-classification challenge

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of the analysis is to use various techniques to train , evaluate a model based on loan risk and build a model that can identify the creditworthiness of borrowers.

## Results

The balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 - Logistic Regression:

	Accuracy: 0.9442676901753825
	
	Precision: 1.0 / 0.87
	
	Recall scores: 1.0 / 0.89

* Machine Learning Model 2 - Logistic Regression w/ ReSampled Data:

	Accuracy: 0.9959744975744975
	
	Precision: 1.0 / 0.87
	
	Recall scores: 1.0 / 1.0

## Summary

 The precision for the logistic regression model, detecting healthy loans (1.0) was accurate and a little less accurate at detecting high-risk one (0.87).
 For recall, the model was accurate at detecting healthy loan (1) but scored  detecting high-risk one (0.89).
 Overall, we suggest an increase in accuracy would be necessery from the prediction results from the logistic regression model considering we're evaluating high-risk loan.

 The precision for the logistic regression model, fit with oversampled data, was accurate at detecting healthy loans (1.0) and a little less accurate at detecting high-risk one (0.87).
 For recall, the model using resampled data was accurate at detecting healthy loan and high-risk loan alike.
 To summarize, the model using resampled data was showed an increase in accuracy at detecting high-risk loan.
 Balanced accuracy score was higher for the resampled data (0.9959 vs 0.9442)
