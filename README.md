# Credit_Risk_Analysis

## Overview of the Analysis
For this assignment, credit card data was used for sampling purposes, then comparing machine learning models to predict credit risk. The analysis used sampling algorithms such as SMOTE, RandomOverSampler, ClusterCentroids and SMOTEEN, along with machine learninr models BalancedRandomForestClassifier and EasyEnsembleClassifier.

## Results

Below are the results from the algorithms used to sample the data:

### Naive Random Oversampling
* Balanced Accuracy Score: 63.6%
* Precision Score: 99%
* Recall: 58%

### SMOTE Oversampling
* Balanced Accuracy Score: 64.8%
* Precision Score: 99%
* Recall: 64%

### ClusterCentroids Undersampling
* Balanced Accuracy Score: 64.4%
* Precision Score: 99%
* Recall: 67%

### SMOTEEN Combination Sampling
* Balanced Accuracy Score: 64.4%
* Precision Score: 99%
* Recall: 58%

### RandomForestClassifier Ensemble Algorithm
* Balanced Accuracy Score: 78.8%
* Precision Score: 99%
* Recall: 95%

### EasyEnsembleClassifier Ensemble Algorithm
* Balanced Accuracy Score: 93.3%
* Precision Score: 99%
* Recall: 95%

## Summary
After analyzing the data from all methods, it appears the ensemble algorithms are more accurate in predicting credit risk. These methods have higher accuracy and recall than the over, under, and combination sampling methods. Of the two ensemble algorithms used in this analysis, I would recommend using the Easy Ensemble Classifier, as it has the higher accuracy of the two algorithms.

However, this method would still require further analysis due to the high rate of false negatives.
