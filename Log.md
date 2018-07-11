# 100 Days Of ML - LOG

## Day 0 : July 6, 2018
**Today's Progress**: Worked on Santander Kaggle Competition: https://www.kaggle.com/c/santander-value-prediction-challenge by working my way through this kernel: https://www.kaggle.com/alexpengxiao/preprocessing-model-averaging-by-xgb-lgb-1-39

## Day 1: July 7, 2018
**Today's Progress**: Santander Kaggle Competition: 

Forked and ran https://www.kaggle.com/alexpengxiao/preprocessing-model-averaging-by-xgb-lgb-1-39. It put me at rank 555 with a score of 1.4

The notebook from the highest level does the following: 
1) data preprocessing, 
2) feature transform, and 
3) xgboost (Extreme Gradient Boosting is an optimized distributed gradient boosting library designed to be highly efficient, flexible and portable that provides a parallel tree boosting, combining many weak learners) and lightgbm (gradient boosting framework that uses tree based learning algorithms; faster training speed and higher efficiency than XGBoost) models. 

In more detail, we do the following: 
1) load the train and test data, drop duplicate columns, round the features, 
2) select features by importance using weak RandomForestRegressor (ensemble of randomized regression trees), 
3) test the training/testing data with Kolmogorov-Smirnov test (used to decide if a sample comes from a population with a specific distribution) as a two-sided test for the null hypothesis (whether independent samples are drawn from the same continuous distribution; if a feature has a different distribution in training set than in testing set, we remove it,
4) add low-dimensional representations as features,
5) define cross-validation methods and models; xgboost and lightgbm are used as base models; hyperparameters are tuned by grid search,
6) average the two base models and submit predictions

## Day 2: July 8, 2018
**Today's Progress**: Santander Kaggle Competition: coded step 1: load train/test data, drop duplicate columns, round features

## Day 3: July 9, 2018
**Today's Progress**: Reading through this kernel for Santander Kaggle Competition:
https://www.kaggle.com/tunguz/yaeda-yet-another-eda
Also, coded step 2: select features by importance using a weak RandomForestRegressor

## Day 4: July 9, 2018
**Today's Progress**:
Coded step 3: test the training/testing data with Kolmogorov-Smirnov test

## Day 5: July 10, 2018
**Today's Progress**:
Coded step 4: add low-dimensional representations as features
