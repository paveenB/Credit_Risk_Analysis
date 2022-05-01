# Credit_Risk_Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  The project is to employ different techniques to train and evaluate models with unbalanced classes.  Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will take a look at the outcomes of different sampling models and the credit risks.

## Results

### Naive Random Oversampling

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/RandomOverSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/RandomOverSamp2.png)

* The balanced accuracy score is 64%
* The high risk precision is about 1% with a sensitivity recall score of 66%
* the low risk precision is about 100% with a sensitivity recall score of 62%

### SMOTE Oversampling

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/SMOTEOverSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/SMOTEOverSamp2.png)

* The balanced accuracy score is 65%
* The high risk precision is about 1% with a sensitivity recall score of 69%
* the low risk precision is about 100% with a sensitivity recall score of 61%

### Cluster Centroids

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/UnderSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/UnderSamp2.png)

* The balanced accuracy score is 65%
* The high risk precision is about 1% with a sensitivity recall score of 69%
* the low risk precision is about 100% with a sensitivity recall score of 40%

### SMOTEENN

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/CombSamp2.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/CombSamp1.png)

* The balanced accuracy score is 54%
* The high risk precision is about 1% with a sensitivity recall score of 72%
* the low risk precision is about 100% with a sensitivity recall score of 57%

### Balanced Random Forest Classifier

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/BalanceRandFor1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/BalanceRandFor2.png)

* The balanced accuracy score is 77%
* The high risk precision is about 3% with a sensitivity recall score of 64%
* the low risk precision is about 100% with a sensitivity recall score of 89%

### Easy Ensemble AdaBoost Classifier

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/EasyEnClass1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/EasyEnClass2.png)

* The balanced accuracy score is 92%
* The high risk precision is about 9% with a sensitivity recall score of 89%
* the low risk precision is about 100% with a sensitivity recall score of 94%

## Summary

Each of the the models used to perform the credit risk analysis showed weak precision in determining if a credit risk is high.  The Ensemble models did bring improve the sensitivity of the high risk credits.  The Easy Ensemble AdaBoost Classifier model shows accuracy of 92% so it detects almost all high risk credit. On another hand, with a low precision, a lot of low risk credits are still falsely detected as high risk which would not do well to the bank's credit strategy or bottomline.  I would not be comfortable in recommending the bank to use any of these models to predict credit risk.






