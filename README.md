# K-means

I implement  K-means clustering algorithm to cluster given three different datasets.

## Datasets
The dataset ﬁles contain features (in 2D) and class labels. 
I didn’t use class labels since K-means is an unsupervised algorithm and does not
need class labels. Scatter plot of the datasets given in Figure 1.

 <p align="center" style="text-align:center"> 
<img src="outputs/datasets.png" width=700><br>
  Figure 1: Three datasets.
</p>

## K-means Algorithm
K-means clustering is a simple and popular type of unsupervised machine learning algorithm, which is used on unlabeled data. 
The goal of this algorithm is toﬁnd groups in the data, with the number of groups represented by the variable
*K*. The algorithm works iteratively to assign each data point to one of *K* groups according to provided features similarity.
Algorithm steps for K-means given as following.

1. Randomly pick *K* observations and set them as initial cluster centers
2. Iterate until cluster assignments stop changing: 
    * For each of the *K* clusters, compute the cluster centroid. The *k*th clustercentroid is the vector of the p feature means for the observations in the *k*th cluster.
    * Assign each observation to the cluster whose centroid is closest (where closest
is deﬁned using Euclidean distance).

When N is number of samples and K is number of clusters, K-means algorithm try to minimize objective function which given as following.


<p align="center"> 
<img src="https://user-images.githubusercontent.com/45906647/90062451-613ef880-dcf0-11ea-9f19-6a3f12496b28.png"  width="500"  />
</p>


## Clustering Results
I implement K-Means class for algorithm and cluster three given dataset with
following conﬁgurations:
* Dataset1: k=3, k=7
* Dataset2: k=2, k=5
* Dataset3: k=3, k=8



