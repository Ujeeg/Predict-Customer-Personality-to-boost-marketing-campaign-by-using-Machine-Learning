# Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning

## DATA 
Data yang di gunakan berasal dari Rakamin Academy (https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/f79daa30fc1a192eaadfc315f6196016587edf5a/marketing_campaign_data.csv)

Jumlah Data Terdiri dari 30 Kolom dan 2240 baris

![View Data](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/de2a9a75d319edafbe4e9e31b092f9296146a55b/Data.png)

## Problem 
Membuat Clustering data menggunakan KMeans

## Fiture Extraction
1. Membuat Kolom Acceptedcmp dengan menjumlah Acceptedcmp1 - Acceptedcmp5
2. Membuat Kolom NumPurcashes dengan menjumlah kolom NumDealsPurcashes, NumWebPurchases, NumStorePurchases, NumCatalogPurchases
3. Membuat Kolom SpendProduct dengan menjumlah kolom MntCoke,MntFruits,MntMeatProducts,MntFishProducts,MntSweetProducts,MntGoldProds
4. Membuat Kolom Age dengan Mengurangi kolom Year_Birth dengan Tahun Pengerjaan
5. Membuat Kolom Age Group 
6. Membuat Kolom convention_rate
7. Membuat kolom children dengan menjumlahkan kidhome dan Teenhome
8. Memperbaiki data marital_status 

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/96099aeda723bfcf720432e40702dab0cb601829/Future%20Extraction.png)

## Drop Data for EDA

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/dc0c1148d367ca72dd664cdb80be61224c52f7d9/Drop%20data.png)


## EDA
1. Numeric data

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/11ba8b7c2c793d4037b1485733e492234edef5e0/Univariate%201.png)  
![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/11ba8b7c2c793d4037b1485733e492234edef5e0/Univariate%202.png)

2. Categorical Data

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/3a510c58996b71d6386cddf491749ed25034cd5f/Univariate%20cat.png)

3. Correlation

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/fd8a911e614404f4f723df074844c5c04a3fac87/Multivariete.png)


4. Age Grup with CVR

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/b2ea1fbf237698cc5231934782d87bf9fe47193d/Age%20group%20EDA.png)

5. Education with CVR
![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/b2ea1fbf237698cc5231934782d87bf9fe47193d/Education%20EDA.png)

## Preprocessing



