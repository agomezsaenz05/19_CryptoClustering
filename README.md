# 19_CryptoClustering
## Find the Best Value for k Using the Original Scaled DataFrame
#### To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.

(Line 10 in Crypto_Clustering.ipynb)


![10-Elbow-Curve](https://github.com/agomezsaenz05/19_CryptoClustering/assets/120424668/47bfd2b4-a90d-442f-9c8c-b1a57badf4da)

## Cluster the Cryptocurrencies with K-Means by Using the Original Data
#### Using hvPlot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.

(Line 17 in Crypto_Clustering.ipynb)

![17-scatter-plot](https://github.com/agomezsaenz05/19_CryptoClustering/assets/120424668/24de89db-47c2-4800-a437-1e4b84aec05a)

## Find the Best Value for k by Using the PCA Data
#### To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.

(Line 25 in Crypto_Clustering.ipynb)

![25-Elbow-Curve](https://github.com/agomezsaenz05/19_CryptoClustering/assets/120424668/35645a05-2ee0-41bb-b2f0-29b58004bb21)

## Cluster the Cryptocurrencies with K-means by Using the PCA Data
#### Using hvPlot, create a scatter plot by setting x="PC1" and y="PC2". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.

(Line 30 in Crypto_Clustering.ipyn)

![30-Scatter-Plot](https://github.com/agomezsaenz05/19_CryptoClustering/assets/120424668/bcdc4c85-a9fb-417a-8473-2ce9575da89d)
