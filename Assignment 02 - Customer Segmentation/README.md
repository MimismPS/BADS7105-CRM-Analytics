# Customer Segmentation

[![](https://img.shields.io/badge/-Python-brightgreen)](#) [![](https://img.shields.io/badge/-Google--Colab-brightgreen)](#) [![](https://img.shields.io/badge/-K--Means-brightgreen)](#)

**Google Colab:** [![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/gist/MimismPS/01cbcb075cbe36c3a56b28e549a69b3a/cutomer-segmentation.ipynb)

## 1. Import Dataset
"Supermarket Data"
<hr>

## 2. Prepare Customer Single View
### Calculate features
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/Calculate%20Features.png" />
<hr>

## 3. Cluster Customers and Compare model performance
</p>
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/Model%20Performance.png" />
<hr>

## 4. Spectral Clustering Clustering
### Cluster PCA Plot
</p>
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/PCA%20Plot.png" />

### Distortion Score Elbow for K-means Clustering
</p>
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/K-mean%20Clustering.png" />

### Number of Customer of Each Clustering
</p>
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/Customer%20each%20clustering.png" />

### Silhouette Plot of K-Means Clustering for 6100 Samples in 4 Centers
</p>
<img src="https://github.com/MimismPS/BADS7105-CRM-Analytics/blob/main/Assignment%2002%20-%20Customer%20Segmentation/Silhouette%20Plot.png" />
<hr>

## Analysis Feature for Clustering

<i><ins>Cluster0 (Looker Customers)</ins></i>:  Low total spend , lowest rencency and average time between visit 

Recommend :

1. Run analysis on cost vs revenue for offering promotions
2. Churn prediction (Lead scoring)


<i><ins>Cluster1  (Researcher Customers)</ins></i>:  Average total spend ,rencency and average time between visit 

Recommend :

1. Daily promotion special
2. Discount special product, BOGO

<i><ins>Cluster2 (Honor Customers)</ins></i>:  Highest total spend, highest rencency,  lowest average between visit

Recommend : 
1. New products
2. Promotion แนะนำเพื่อนให้มาซื้อจะได้รับส่วนลด


<i><ins>Cluster3 (Richer Customers)</ins></i>:  High total spend, high rencency, low average between visit 

Recommend :

1. Upsell 
2. Voucher เมื่อซื้อสินค้าในแต่ละเดือนครบตามจำนวนเงินที่กำหนด 
