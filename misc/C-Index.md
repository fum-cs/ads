The C-index measure is a clustering evaluation metric that compares the average distance within clusters to the average distance between clusters. It is defined as:

$$C-Index = \frac{W - W_{min}}{W_{max} - W_{min}}$$

where W is the sum of the distances between pairs of points that belong to the same cluster, W_min is the minimum possible value of W, and W_max is the maximum possible value of W. The range of C-index measure is from 0 to 1, where lower values indicate better clustering quality.

The minimum value of C-index is 0, which means that W is equal to W_min. This can happen when the clusters are compact and well-separated, such that the distances within clusters are much smaller than the distances between clusters.

The maximum value of C-index is 1, which means that W is equal to W_max. This can happen when the clusters are dispersed and overlapping, such that the distances within clusters are much larger than the distances between clusters.