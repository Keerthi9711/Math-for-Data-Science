# k-means clustering

The goal is to find clusters such that the observations within each cluster are quite similar to each other, while observations in different clusters are quite different from each other.
Being a clustering algorithm, k-Means takes data points as input and groups them into k clusters. This process of grouping is the training phase of the learning algorithm.
The result would be a model that takes a data sample as input and returns the cluster that the new data point belongs to, according the training that the model went through.
Basic data analysis is performed as a Smoke test for the quality of data, to handle null values or non-categorical datatypes for our use case.
Given data is divided into training data and test data.
Using k-means algorithm, model is trained with the training set of the input data.
Optimization techniques like Elbow rule, Silhouette coefficient are used to find the optimal k value.
Finally the prediciton level of the model is found out using the test data with optimal clusters.
