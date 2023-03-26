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
1. Handling Data Null

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/4fefdb39351632cdcbe848faca342b9281d0c8b3/Null%20data.png)

2. Handling Data Duplicate

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/4fefdb39351632cdcbe848faca342b9281d0c8b3/Duplicate%20data.png)

## Clustering
### 1. Data Selection for Clusterring

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/e563ded44807e818fcc580a70321c7ab6993ca7f/Data%20selection%20clustering.png)'

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/e563ded44807e818fcc580a70321c7ab6993ca7f/Data%20selection%20clustering%20LMRFC.png)

### 2. KMeans

![]{https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/881c073f745ec774bd44d3f6007b44f286c7fba8/Kmeans.png)

### 3. Silhouette Score

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/881c073f745ec774bd44d3f6007b44f286c7fba8/Shillouete%20score.png)

### 4. Clustering Kmeans

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/7af07da2dd56dc58f845e44e92ce601fbdd3d0e7/query%20kmeans.png)

### 5. VIsualisasi PCA

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/7af07da2dd56dc58f845e44e92ce601fbdd3d0e7/PCA.png)

### 6. Total Customer Tiap Cluster

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/7af07da2dd56dc58f845e44e92ce601fbdd3d0e7/Total%20custemer%20per%20cluster.png)

### Interpretasi Cluster

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/7af07da2dd56dc58f845e44e92ce601fbdd3d0e7/Cluster%20tables.png)

![](https://github.com/Ujeeg/Predict-Customer-Personality-to-boost-marketing-campaign-by-using-Machine-Learning/blob/7af07da2dd56dc58f845e44e92ce601fbdd3d0e7/CLuster%20table%202.png)



1 . Risk of Churn (Cluster 2):
- Total customer 537 (paling tinggi ke 2)
- Recency 74
- Age 44 - 59
- cvr 1.866 (paling rendah)
- income 38M/year (paling rendah)
- Visit 6.235 (paling tinggi)
- Total Purchase 9.132 (paling rendah)
- Spend Product 150K (paling rendah)
- campaign accepted 0.093

berdasarkan data di atas dapat di lihat bahwa jenis customer risk of churn merupakan customer yang memiliki tingkat recency tinggi berarti sudah lama tidak mengunjungi ecommers ini, namun dapat di lihat pada tingkat visit pagenya cukup tinggi menandakan customers sering melihat barang - barang namun tidak melakukan pembelian. hal tersebut dapat terjadi di mungkinkan karena kurang baiknya search engine pada ecommers yang menyebabkan pembeli tidak bisa menemukan barang yang di inginkan atau mungkin ada kendala pada payment method dan jasa pengiriman. dan juga peromo yang kurang tepat penggunaannya.

2. Low Spender (Cluster 0)
- Total customer 549 (paling tinggi )
- Recency 23,071 (paling tinggi)
- Age 44 - 56
- cvr 1.921
- income 3.9M
- Visit 6.169
- Total Purchase 9.084
- Spend Product 150K
- campaign accepted 0.118

Pada Low spender memiliki tinggkat recency yang normah tapi pada total visit sangar tinggi dan tinkat campaign accepted yang rendah. hal ini dapa menggambarkan bahwa customer low spender merupakan customer yang hanya melihat barang saja dan membeli ketika promo yang diberikan cocok. Hal tersenbut juga bisa menggambarkan bawa customer kemungkinan kesulitan untuk mendapatkan barang yang cocok, yang menandakan ada kekurang pada Search Engine.

3. Mid Spender (Cluster 3)
- Total customer 490
-Recency 48,7
- Age 63 - 71
- cvr 6.942
- income 66M
- Visit 4.329
- Total Purchase 20.741(paling tinggi)
- Spend Product 1M
- campaign accepted 0.435

pada customer Mid spender dapat dilihat bahwa tingkat puchased item memili nilai paling tinggi, dan total visit yang cukup rendah, selain itu total campagn yang di  ambil termasuk normal atau berada di tengah -tengah. menandakan bahwa customer pada Mid spender merupakan customer yang tepat beli. Dimana customer hanya membeli barang sesuai dengan yang di inginkan, dan lenbih suka membeli barang yang tidak terlalu mahal.

4. High Spender (Cluster 2)
- Total customer 454 (paling rendah)
- Recency 49.460
- Age 41-52
- cvr 7.547
- income 70M
- Visit 4.293 (paling rendah)
- Total Purchase 22.421
- Spend Product 1.2M
- campaign accepted 0.623

pada customer high spender memiliki total customer yang paling rendah, dan tingkat visit yang palinf rendah juga, selain itu untuk total accept campagn merupakan yang paling tinggi. Hal tersebut menggambarka bahwa customer high spender merupakan customer yang tepat beli tetapi lebih suka menggunakan promo yang ada pada ecommers.

Buisness Reccomendation

1. Memperbaiki search engine dan product recommendation
2. Melakukan pengecekan pada pageview, ada kemungkinan customer mengalami kendala pada metode pembayaran dan jasa kirim yang kurang lengkap
3. Memaksimalkan Mid spender dengan memberikan promo dalam bentuk notifikasi email, atau pun notifikasi aplikasi
4. Untuk Risk of churn membuat notifikasi remainder untuk product yang ada pada keranjang atau barang yang di cari sebelumnya
5. Low spender bisa memberikan notifikasi promo atau pengingat pada email dimana pada low spender memiliki tingkat recency yang cukup tinggi, kemungkinan customer sudah menguninstall applikasi cukup tinggi




