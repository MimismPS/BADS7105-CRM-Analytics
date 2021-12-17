# Campaign Response Model

[![](https://img.shields.io/badge/-Logistic--Regression-brightgreen)](#) [![](https://img.shields.io/badge/-XGBoost-brightgreen)](#) [![](https://img.shields.io/badge/-Python-brightgreen)](#) [![](https://img.shields.io/badge/-Google--Colab-brightgreen)](#) 

**Google Colab:** **Google Colab:** [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10SerbQKeCaJ-6413X1CZHWMz5iGJvRLG#scrollTo=PZj402q7JEqm)

## Datasets
1. "Retail Data Response"
2. "Retail Data Transactions"

## 1. Data Preparation
Since the last date of the data is 16 March 2015, the campaign date is assumed to be 17 March 2015.
RFM model will be used to predict campaign response. Recency is calculated.
1.1 Create data set with RFM variables
1.2 Create data set with CLV variables

## 2. Calculating Response Rate
Data is imbalanced.


## 3. Creating Train and Test Dataset

## 4. Fixing Imbalanced with SMOTE

## 5. XGBoost Model - SMOTE CLV

## 6. Hyper Parameter Tuning - Grid Search
By adding:
1. subsample --> Represents the fraction of observations to be sampled for each tree.
2. alpha --> L1 regularization on the weights (Lasso Regression). When working with a large number of features, it might improve speed performances.
3. lambda --> L2 regularization on the weights (Ridge Regression). It might help to reduce overfitting.

## 7. ROC Curve
