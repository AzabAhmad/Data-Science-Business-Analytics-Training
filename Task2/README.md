## Prediction using Unsupervised ML
From the given 'Iris' dataset we'll predict the optimum number of clusters and represent it visually.
1- First of all we'll prepare the data and select a proper clustering algorithm:
We'll prepare the data for clustering using the StandardScaler to scale the whole data set.
For the sake of simplicity we'll use a K-Means model.
2- There are several methods of how to determine (visually) the right number of clusters. We will use the elbow-plot method.
3- To visualize our clusters in a 2D space, we need to use dimension reduction techniques, I've used PCA.
