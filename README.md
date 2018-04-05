# Behavior Modeling 
Behavior Modeling of Children

The whole procedure consists of
- Preprocessing time-id-location data with linear interpolation and smoothing 
- Slice the whole trajectory into chunks
- Reduce the dimension of each chunk with PCA and cluster with K-means
- Compute the normalized histogram of the cluster indices
- Train classifiers which map the histogram to the characteristic of each child using xgboost 

