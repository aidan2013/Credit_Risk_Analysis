# Credit_Risk_Analysis

## Overview of the analysis

The purpose of this project is to build and evaluate models with unbalanced classes using resampling in order to predict credit risk. We will be using the data from LoanStats2019Q1.csv for this analysis. 

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Over and Under Sampling
----------------
**Random Oversampling Model**

- 63% balanced accuracy score 
- The total precision is 99% with a recall of 64%. 

![image](https://user-images.githubusercontent.com/91445591/165002338-a4b7cb5c-88d1-42a1-aea1-54745d974693.png)

**SMOTE Oversampling Model**

- 63% balanced accuracy score 
- The total precision is 99% with a recall of 67%. 

![image](https://user-images.githubusercontent.com/91445591/165002448-6a190e3f-45d1-47b5-bde0-52df84b2354f.png)

**Cluster Centroids Understampling**

- 51% balanced accuracy score 
- The total precision is 99% with a recall of 46%. 

![image](https://user-images.githubusercontent.com/91445591/165003237-1b37a803-fd27-4b47-a50a-2f97233db27d.png)

**SMOTEEN Combination Over and Understampling**

- 63% balanced accuracy score 
- The total precision is 99% with a recall of 57%. 

![image](https://user-images.githubusercontent.com/91445591/165003310-38448d02-0114-4dcc-89ac-f7182aa56ec8.png)

### Ensemble Learners
----------------

**Balanced Random Forest Classifier**

- 78% balanced accuracy score 
- The total precision is 99% with a recall of 91%

![image](https://user-images.githubusercontent.com/91445591/165003491-493c1e8d-530e-4a99-b885-1c26da1766aa.png)

**Easy Ensemble AdaBoost Classifier**

- 91% balanced accuracy score 
- The total precision is 99% with a recall of 95%

![image](https://user-images.githubusercontent.com/91445591/165003533-7b51c527-4174-4bcb-b93d-1f0d5e60e6f7.png)

## Summary

All of the models have almost a 100% precision score. Although this is a great score, when reviewing the high_risk precision data, the score is less than 10% on all models. These models may not be the best to follow when the main focus is high risk credit. Easy Ensemble Classifier has the highest recall and precision credit compared to all other models. Although this model has the highest recall, there is still a significant number of low risk credit that is being predicted as high risk. This would be the recommended model to the executive team if they have a more conservative lending strategy. 
