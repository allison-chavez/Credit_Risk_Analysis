# Credit_Risk_Analysis

## Project Overview
The purpose of this analysis was to complete and compare machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to compare credit risks. Once both machine models are complete I will use the data gathered to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results

Logistic regression:


Naive Random sampling:
- accuracy score: 0.64
- precision: 0.99
- recall scores: 0.56
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/naive.png)



Smote OverSampling:
- accuracy score:  0.65
- precision: 0.99
- recall scores: 0.56
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/smote.png)



Undersampling:
- accuracy score: 0.54
- precision: 0.99 
- recall scores: 0.40
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/undersampling.png)




Combo:
- accuracy score: 0.65
- precision: 0.99
- recall scores: 0.56
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/combo%20over:under.png)





Balanced Random Forest: 
- accuracy score: 0.87
- precision:
  - macro avg: 0.51           
  - weighted avg: 0.99  
- recall scores:
   - macro avg: 0.79     
   - weighted avg: 0.87
   
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/balancedRandomForest.png)





Easy Ensemble Classifier:
- accuracy score: 0.93
- precision: 0.99
- recall scores: 0.94
![alt_text](https://github.com/allison-chavez/Credit_Risk_Analysis/blob/main/images/EasyEnsemble.png)


## Summary
machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
