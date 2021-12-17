# Campaign Response Model

[![](https://img.shields.io/badge/-RFM-brightgreen)](#) [![](https://img.shields.io/badge/-CLV-brightgreen)](#) [![](https://img.shields.io/badge/-XGBoost-brightgreen)](#) [![](https://img.shields.io/badge/-Python-brightgreen)](#) [![](https://img.shields.io/badge/-Google--Colab-brightgreen)](#) 

**Google Colab:** **Google Colab:** [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10SerbQKeCaJ-6413X1CZHWMz5iGJvRLG#scrollTo=PZj402q7JEqm)

## Datasets
1. "Retail Data Response"
2. "Retail Data Transactions"
<hr>

## 1. Data Preparation
Since the last date of the data is 16 March 2015, the campaign date is assumed to be 17 March 2015.

RFM model will be used to predict campaign response. Recency is calculated.

1.1 Create data set with RFM variables

1.2 Create data set with CLV variables
<hr>

## 2. Calculating Response Rate
Data is imbalanced.

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Response%20Distribution.png" />
<hr>

## 3. Creating Train and Test Dataset

### RFM

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20Frequency%20-%20RFM.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20Monetary%20-%20RFM.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Frequency%20and%20Monetary%20-%20RFM.png" />

### CLV

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20Frequency%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20Monetary%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20AOU%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Recency%20and%20Ticket%20Size%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Frequency%20and%20Monetary%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Frequency%20and%20AOU%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Frequency%20and%20Ticket%20Size%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Monetary%20and%20AOU%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/Monetary%20and%20Ticket%20Size%20-%20CLV.png" />

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/AOU%20and%20Ticket%20Size%20-%20CLV.png" />

<hr>

## 4. Fixing Imbalanced with SMOTE - XGBoost Model (SMOTE CLV)

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/XGBoost%20model%20-%20SMOTE%20CLV.png" />

<hr>

## 5. Hyper Parameter Tuning - Grid Search
By adding:
1. subsample --> Represents the fraction of observations to be sampled for each tree.
2. alpha --> L1 regularization on the weights (Lasso Regression). When working with a large number of features, it might improve speed performances.
3. lambda --> L2 regularization on the weights (Ridge Regression). It might help to reduce overfitting.

<hr>

## 6. ROC Curve

<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2004%20-%20Campaign%20Response%20Model/ROC%20Curve.png" />

AUC Score for training data = 0.709
AUC Score for test data = 0.704
