# Kmeans-from-Scratch

For an input of a random data set with N data points, we implement a K-means parameter estimation function that returns K centroids and N labels.
I use the sklearn function datasets.make_blobs for generating clusters to test the algorithm.
The centroids are the sample mean of each cluster, the labels are the cluster indices of each data point.
The K-means algorithm is sensitive to the initialization of the centroids and n_init is the number of initializations we run.
