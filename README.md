# credit-risk-classification

## Overview of the Analysis

As a risk analyst, creating a credit risk model is a more efficient way to evaluate loan risk than manual record evaluation. To predict loan risk, we use a supervised machine learning model (Logistic Regression) to classify loan risk as high or low based on historical lending activity data from a peer-to-peer lending services company. In addition to training and classifying data, we can use evaluation tools and resampling methods to improve the accuracy of the model's predictions.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 0.9520
  * Precision: 
    * label 0 (healthy loan): 1
    * label 1 (high-risk loan): 0.85
  * Recall scores:
    * label 0 (healthy loan): 0.99
    * label 1 (high-risk loan): 0.91



* Machine Learning Model 2:
  * Accuracy: 0.9937
  * Precision:
    * label 0 (healthy loan): 1
    * label 1 (high-risk loan): 0.84
  * Recall scores:
    * label 0 (healthy loan): 0.99
    * label 1 (high-risk loan): 0.99

## Summary

After comparing the evaluation results of model 1 and model 2, it was found that model 2 had higher accuracy and recall scores than model 1, despite a slightly lower precision score for label 1. Based on these findings, I would recommend using model 2, which utilizes resampled data.
