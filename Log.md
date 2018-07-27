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

## Day 4: July 10, 2018
**Today's Progress**:
Coded step 3: test the training/testing data with Kolmogorov-Smirnov test

## Day 5: July 11, 2018
**Today's Progress**:
Coded step 4: add low-dimensional representations as features

## Day 6: July 12, 2018
**Today's Progress**:
Coded step 5: define cross-validation methods and models

## Day 7: July 13, 2018
**Today's Progress**:
Coded step 6: average the two base models

## Day 8: July 14, 2018
**Today's Progress**:
Went through this kernel: https://www.kaggle.com/scirpus/the-data-contains-the-target

## Day 9: July 15, 2018
**Today's Progress**:
Went through this kernel: https://www.kaggle.com/scirpus/qr-decomposition Learning how to handle sparse data

## Day 10: July 16, 2018
**Today's Progress**:
Went through this kernel: https://www.kaggle.com/shivamb/dataset-decomposition-techniques, eigenvalues etc

## Day 11: July 17, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/johnfarrell/giba-s-property-extended-result

## Day 12: July 18, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/titericz/the-property-by-giba

## Day 13: July 19, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/tezdhar/breaking-lb-fresh-start

## Day 14: July 20, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/johnfarrell/breaking-lb-fresh-start-with-lag-selection

## Day 15: July 21, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/the1owl/love-is-the-answer

## Day 16: July 22, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/bhaveshthaker/svp-exploratory-data-analysis-eda-and-modeling

## Day 17: July 23, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/ogrellier/feature-scoring-vs-zeros

## Day 18: July 24, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/sudalairajkumar/simple-exploration-baseline-santander-value

## Day 19: July 25, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/ogrellier/feature-scoring-vs-zeros

## Day 20: July 26, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/ashishpatel26/blending

## Day 21: July 27, 2018
**Today's Progress**:
Working through this kernel: https://www.kaggle.com/sggpls/pipeline-kernel-xgb-fe-lb1-39


