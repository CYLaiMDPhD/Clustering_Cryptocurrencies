# Cryptocurrencies

*Note: This repository was created to fulfill an assignment (Module 18 Challenge) for the UC Berkeley Data Analytics and Visualization Bootcamp. Submitted on 2-24-22 for grading.*


## Summary Overview
This project demonstrates some fundamental steps in unsupervised machine learning using the SciKit Learn module and a sample dataset of cryptocurrency properties. The data was cleaned and transformed using pandas. Specifically, the algorithm and proof type features were converted to 96 features by one-hot encoding. Feature dimensions were then reduced to three components by principle component analysis and scaled using StandardScaler. Finally, a k-means algorithm as applied to cluster data into four clusters and visualized using hvplot. 


**Data Source:** 
A dataset of crytocurrency data provided by course as csv file.


**Figure 1: Elbow Curve to Determine Best Number of Clusters for K-Means Model**

![Fig1.png](/Images/Fig1.png)



**Figure 2: 3D Plot of Cryptocurrencies Clustered by K-Means**

![Fig2.png](/Images/Fig2.png)


Using k-means, a common unsupervised machine learning algorithm the cryptocurrencies in our dataset was grouped into four distinct clusters on three principle components. Two popular cryptocurrencies, Bitcoin and Ethereum, were clustered into class 1 (magenta diamonds in Figure 2) along with other lesser known coins. The BitTorrent coin stands alone in its own cluster (orange X in Figure 2). These clustering results could potentially be used to further train a supervised machine learning model in order to recommend or predict coin values, fluctuations, or other data. However, as our dataset contained no information about coin prices or trading metrics, the clusters determined here have no inherent properties linked to real world monetary values.



---
## Module Lessons and Activities

- Overview and introduction to unsupervised machine learning
- Data Preparation and preprocessing for machine learning
- KMeans algorithm
	- Generating elbow curves
- Principle Component Analysis
- Hierarchical Clustering
	- Generating Dendrograms


---
## Files for grading

- crypto_clustering.ipynb