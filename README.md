
# Crypto Clustering Analysis

This code combines financial Python programming with unsupervised learning to cluster cryptocurrencies based on performance in different periods, using K-Means and Principal component Analysis (PCA).


## Data Set
Data contains returns (price change) data of cryptocurrencies in several periods, in a CSV file.
## Used Algorithms
- K-Means clustering
- K-Means clustering after applying PCA
## Steps
The steps of the analysis are broken out into the following sections:

* Import the Data
* Prepare the Data
* Find the Best Value for `k` Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for `k` Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results