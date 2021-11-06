# Cryptocurrencies

## Overview 
Creating an analysis report regarding cryptocurrencies trading market for Accountability Accounting, a prominent investment bank to offer a cryptocurrency investment portfolio for its customers.

This project is using unsurpervised learning tools, preprocessing cryptocurrency data, reducing data dimensions using PCA, clustering cryptocurrency using K-means and visualizing cryptocurrencies results.

## Result

#### Clustering Crytocurrencies Using K-Means - Elbow Curve
Create the Elbow Curve to determine the best k value, the number of clusters that applying in K-Means model. As the figure below, we will use k=4 in K-Means model to group the data into 4 clusters. 
![](Results/Figure1.png)

#### 3D-Scatter with Clusters
Using PCA algorithm to reduce data dimensions to 3 principal components and create 3D-scatter with 4 clusters. As the figure below, class 0 and class 1 have the most cryptocurrencies. However, class 3 has only 1 cryptocurrency, it should be the outlier based on its distribution.

![](Results/Figure2.png)

#### 2D-Scatter plot with TotalCoinsMined vs TotalCoinSupply
Scale and plot the scatter plot for 2 cryptocurrency feature. This figure isn't obviously performing the differences between classes. Compare to the 3D-scatter plot above, using PCA algorithm is a better way to show the different.
![](Results/Figure3.png)
