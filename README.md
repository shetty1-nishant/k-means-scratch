# k-means-scratch
In this project, K-means algorithm is code is written from scratch.K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data.The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K.
Also the application of k-means for image compression is shown





K-means algorithm:
  step 1: Choose no of cluster-'k' value
  step 2: Randomly select initial data points=>initial data points represent each cluster
  step 3: measure the distance between each data points and cluster
  step 4: assign the points each data point
  step 5: calculate the mean of each cluster
  step 6: repeat 3-5
Pseudo-code of k-means:
  Input:k, set of data points x1,x2,x3,.............,xn
  Place centroids c1,c2,c3,...........,ck at random location
  Repeat until convergence:
    for each xi
      find nearest centroid ci
      assign the point xi to clusters
    for each cluster j=1,2,3,.....,k
      new centroid ci= mean of all points xi assigned to cluster j in previous step
      stop when clusters assignment doesn't change
