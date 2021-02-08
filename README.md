# Credit_Risk_Analysis

## Overview
In this project we want to take a look at predicting credit risk using several machine learning models. We will be using the following algorithms to train the models:

1.) RandomOverSampler

2.) SMOTE

3.) ClusterCentroids

4.) SMOTEENN

5.) BalancedRandomForestClassifier

6.) EastEnsembleClassifier

Taking the results from the models we will evaluate the performance and make a decision if they should be used to predict credit risk.

## Results
### RandomOverSampler Model
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/random%20oversampler.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/random%20oversampler%20matrix.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/random%20oversampler%20report.png"></p>
  
  - The Balanced accuracy test using the RandomOverSampler Model is 65% with a high_risk precison of 1% and recall of 61%.
  
  ### SMOTE Model
 <p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20accuracy%20test.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20matrix.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20classification%20report.png"></p>

- The balanced accuracy test using the SMOTE model is 65% with a high risk precision of 1% and a recall of 42%.

### ClusterCentroids Model
 <p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/Cluster%20balanced%20score.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/Cluster%20classification%20report.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/Cluster%20classification%20report.png"></p>
  
- The Balanced accuracy test using the ClusterCentroids Model is 54% with a high risk precision of 1% and a recall of 42%.

### SMOTEENN Model
 <p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20accuracy%20test.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN%20matrix.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN%20classification%20report.png"></p>
  
- The Balanced accuracy test using the SMOTEENN Model is 65% with a precision of 1% and a recall of 58%.

### BalancedRandomForestClassifier Model
 <p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/balanced%20forest%20accuracy.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/balanced%20forest%20matrix.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/balanced%20forest%20classification%20report.png"></p>
  
 - The Balanced accuracy test using the BalancedRandomForestClassifier is 79% with a high risk precision of 3% and a recall of 87%.
 
 ### EasyEnsembleClassifier Model
  <p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/EEC%20balanced%20accuracy%20score.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/EEC%20matrix.png"></p>
<p align="center">
  <img src="https://github.com/ItsFlowin/Credit_Risk_Analysis/blob/main/Resources/EEC%20classification%20report.png"></p>
  
 - The Balanced accuracy test using the EasyEnsembleClassifier is 93% with a high risk precision of 9% and a recall of 94%.
 
 ## Summary
 
 
