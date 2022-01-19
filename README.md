# Cryptocurrencies

# Project Overview
The basis of this project was to use unsupervised learning machine models to analyze cryptocurrencies according to their features.

# Results
When all of the preprocesssing and cleaning has been done to the data, we are left with a total of 532 tradeable cryptocurrencies

## K-Means - Elbow Curve

Shown in the K-means method producing an elbow curve on the values from 1 to 10

![image](https://user-images.githubusercontent.com/88358771/150054627-2e357714-3a7a-47e5-860b-98b28157eb01.png)

The optimal k value or the bend of our elbow curve is at 4, so 4 clusters should be used to categorize the crypto

## Visualized Results

![image](https://user-images.githubusercontent.com/88358771/150054760-19322551-6c71-4877-910d-d8d3d4a4f823.png)

This is a 3-D scatter plot created using the PCA algorithm to reduce the dimensions of the cryptocurrencies to 3 components.

![image](https://user-images.githubusercontent.com/88358771/150055069-3c0da23f-97f9-4feb-913d-909d190a5131.png)

As we can see in this table, most of the crypto's are part of class #0 and #1

![image](https://user-images.githubusercontent.com/88358771/150055159-e2fcec37-a84d-42e9-bdaf-4126471a1995.png)

By using this 2-D scatter plot, and plotting from two crypto currenct features does a great job of not seperating the different classes. Out of all of the models used I would recommend this PCA algorithim to correctly visual the data.

# Summary
After identifying the 532 classifications of cryptocurrences based on similar features, the data in each group should be looked at further to truly identify the potential or loss for the clients.


