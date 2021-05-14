K-Medoids is similar to K-means algorithm with the only difference of using the actual data points as centroids.

# Image compression using K-Medoids
(1) Initialize the k cluster centers Cj , j = 1,...,k.
(2) Iterate until convergence:
   (2.1) Update the cluster assignments for every data point xi: rij = 1 if j = argmin(j) D(xi; Cj ), and
   rij = 0 otherwise, where D denotes the distance function.
   (2.2) Update the centers Cj for each cluster j: choosing another representative if necessary.
