# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy: 0.952 - The model was about 95.2% accurate
  * Precision: (0, 100), (1, 85) - The model was 100% precise in predicting healthy loans and 85% precise in      predicting high-risk loans
  
  * Recall: (0, 0.99), (1, 0.91) - For the healthy loans, the model got 99/100 right. For the high risk loans, the model got 91/100 right



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy: 0.994 - The model was about 99.4% accurate
  * Precision: (0, 100), (1, 84) - The model was 100% precise in predicting healthy loans and 84% precise in      predicting high-risk loans
  
  * Recall: (0, 0.99), (1, 0.99) - For the healthy loans, the model got 99/100 right. For the high risk loans, the model got 99/100 right


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* I would recommend to use the oversampled model. It performs best because its accuracy and recall scores are higher than the regularly sampled model

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* Performance does depend on whether you are trying to predict 0s or 1s, which is why it is important to use the model which is more accurate

If you do not recommend any of the models, please justify your reasoning.
* I would not recommend to use the regularly-sampled model when one can get more accurate results with t
