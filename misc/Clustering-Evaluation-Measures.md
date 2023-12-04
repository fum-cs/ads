The following measures for clustering validation has been taught (Some in both Classification & Clustering):

* TP, TN, FP, FN 
* [Precision & Recall](https://en.wikipedia.org/wiki/Precision_and_recall)
* Purity
* Match
* F-Measure
* Jaccard
* Rand Statistic
* BetaCV
* C-index
* Silhouette


Some notes:

## BetaCV

The BetaCV measure is a clustering evaluation metric that compares the average distance within clusters to the average distance between clusters. It is defined as:

$$betaCV = \frac{W}{B}$$

where $W$ is the average within-cluster distance and $B$ is the average between-cluster distance. The range of BetaCV measure is from 0 to infinity, where lower values indicate better clustering quality. 

A value of 0 means that all points are in the same cluster and have zero distance from each other. This can happen when all the points are in the same cluster and have zero distance from each other. In this case, the average within-cluster distance W is zero, and the average between-cluster distance B is undefined.


## C-index

The C-index measure is a clustering evaluation metric that compares the average distance within clusters to the average distance between clusters. It is defined as:

$$C-Index = \frac{W - W_{min}}{W_{max} - W_{min}}$$

where W is the sum of the distances between pairs of points that belong to the same cluster, W_min is the minimum possible value of W, and W_max is the maximum possible value of W. The range of C-index measure is from 0 to 1, where lower values indicate better clustering quality.

The minimum value of C-index is 0, which means that W is equal to W_min. This can happen when the clusters are compact and well-separated, such that the distances within clusters are much smaller than the distances between clusters.

The maximum value of C-index is 1, which means that W is equal to W_max. This can happen when the clusters are dispersed and overlapping, such that the distances within clusters are much larger than the distances between clusters.