# Credit Risk Analysis

## Overview of the analysis

### Purpose

We were tasked to use different techniques to train and evaluate the models to predict credit card risk.  We were provided a CSV that contained data from lendingClub to use for the analysis.  We will use Python and imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling and use different supervised machine learning models for our analysis.

Below are the six supervised machine learning models we used for our:

1.  Naive Random Oversampling
2.  SMOTE Oversampling
3.  Cluster Centroid Undersampling
4.  SMOTEENN Sampling
5.  Balanced Random Forest Classifying
6.  Easy Ensemble Classifying


## Results

Below is the balanced accuracy score and the precision and recall scores of all six machine learning models

### 1. Naive Random Oversampling:</u></b>

<b>Balanced Accuracy Score: </b>.66 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.58 

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/NaticeRandomOversampling.png?raw=true" width="auto" height="auto">

### 2. SMOTE Oversampling

<b>Balanced Accuracy Score: </b>.65 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.68

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/Smote.png?raw=true" width="auto" height="auto">


### 3. Cluster Centroid Undersampling

<b>Balanced Accuracy Score: </b>.54 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.40

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/ClusterCentroidUndersampling.png?raw=true" width="auto" height="auto">

### 4. SMOTEENN Sampling

<b>Balanced Accuracy Score: </b>.64 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.57

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/Smoteenn.png?raw=true" width="auto" height="auto">


### 5. Balanced Random Forest Classifying

<b>Balanced Accuracy Score: </b>.77 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.87

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/BalancedRandomForestClassifying.png?raw=true" width="auto" height="auto">


### 6. Easy Ensemble Classifying

<b>Balanced Accuracy Score: </b>.93 <br>
<b>Precision Score: </b>.99 <br>
<b>Recall Score: </b>.94

<img src="https://github.com/andralobo/Module17-Challenge/blob/main/Resources/EasyEnsembleClassifying.png?raw=true" width="auto" height="auto">


## Summary

After reviewing the balanced accuracy score and the precision and recall scores of all six machine learning models we have concluded that Easy Ensemble Classifying model had the best results over the others and would recommend this model.   
