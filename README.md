# CryptoClustering

### The mission is to use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes

> Find the Best Value for k by Using the Scaled DataFrame using the elbow method algorithm to find the best value for k. Using the elbow method helps answer the following question: What's the best value for k? 
Cluster the Cryptocurrencies with K-Means by Using the Scaled DataFrame
Initialize the K-means model with best value for k.
Fit the K-means model by using the scaled DataFrame.
Predict the clusters for grouping the cryptocurrencies by using the scaled DataFrame. Review the resulting array of cluster values.

### Optimize the Clusters with Principal Component Analysis
> For a deeper analysis we turn to PCA.
> Use the PCA model to reduce the features to three principal components.
Get the explained variance to determine how much information can be attributed to each principal component.
> Answer the following question: What's the total explained variance of the three principal components?
Create a new DataFrame from the scaled PCA data. Be sure to set the coin_id index from the original scaled DataFrame as the index for the new DataFrame. Review the first five rows of the DataFrame. 

### Cluster the Cryptocurrencies with K-means by Using the PCA DataFrame 

> Initialize the K-means model with the best value for k.
Fit the K-means model by using the PCA data
Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values.
Create a copy of the scaled PCA DataFrame, and then add a new column of the predicted clusters.

### Visualize and Compare the Results

> Created a composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original scaled DataFrame with the one that you created from the scaled PCA DataFrame.
Created a composite plot by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original scaled DataFrame with those that resulted from the scaled PCA DataFrame. 
