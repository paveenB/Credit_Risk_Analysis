# Credit_Risk_Analysis

## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  The project is to employ different techniques to train and evaluate models with unbalanced classes.  Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we will take a look out the outcomes of different sampling models.

## Results

### Naive Random Oversampling

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/RandomOverSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/RandomOverSamp2.png)

* The balanced accuracy score is 64%
* The high risk precision is about 1%
* the low risk precision is about 100%

### SMOTE Oversampling

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/SMOTEOverSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/SMOTEOverSamp2.png)

* The balanced accuracy score is 65%
* The high risk precision is about 1%
* the low risk precision is about 100%

### Cluster Centroids

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/UnderSamp1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/UnderSamp2.png)

### SMOTEENN

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/CombSamp2.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/CombSamp1.png)

### Balanced Random Forest Classifier

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/BalanceRandFor1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/BalanceRandFor2.png)

### Easy Ensemble AdaBoost Classifier

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/EasyEnClass1.png)

![This is an image](https://github.com/paveenB/Credit_Risk_Analysis/blob/main/EasyEnClass2.png)







