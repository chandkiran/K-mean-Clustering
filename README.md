# K-Means Clustering Repository

This repository contains two implementations of the K-Means clustering algorithm, showcasing its application in unsupervised machine learning. The primary focus is on a custom implementation from scratch and an analysis using a provided customer dataset.

## Table of Contents
- [Overview](#overview)
- [K-Means from Scratch](#k-means-from-scratch)
- [Customer Segmentation Analysis](#customer-segmentation-analysis)
- [Elbow Method for Optimal Clusters](#elbow-method-for-optimal-clusters)


## Overview
K-Means clustering is an unsupervised machine learning algorithm used for partitioning datasets into distinct groups based on feature similarity. This repository includes:
- A custom implementation of the K-Means algorithm from scratch.
- An application of the K-Means algorithm on a custom dataset for customer segmentation, with data visualization techniques.

## K-Means from Scratch
The `kmean-scratch` file contains a complete implementation of the K-Means clustering algorithm developed from the ground up. Key features include:
- Initialization of centroids.
- Assignment of data points to the nearest centroid.
- Updating centroids based on the mean of assigned data points.
- Iterative refinement until convergence.

### Code Snippet
```python
# Example of K-Means from scratch implementation
class KMeans:
    def __init__(self, n_clusters=2, max_iter=100):
        # Initialization code
        ...

