# K-Means-Clustering-from-Scratch
Implementation of K-Means Clustering from Scratch in 2D Space

Problem Statement

Clustering is a fundamental unsupervised learning technique used to identify patterns or groups in data. The goal of this project is to implement the K-Means clustering algorithm from scratch to classify randomly generated data points into 𝐾 clusters. Unlike pre-built libraries, this project involves manual computation of cluster assignments, iterative updates of cluster centers, and convergence verification. The implementation also aims to provide a clear visualization of how cluster centers move over iterations to form the final clusters.


Methodology
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1. Data Generation:

Simulate synthetic data points in R^2 space using Gaussian (normal) distributions for three distinct clusters.

2. Cluster Initialization:

Manually initialize 𝐾 cluster centers in 2D space.

3. Distance Calculation:

Compute the Euclidean distance between each data point and all cluster centers.

4. Cluster Assignment:

Assign each data point to the cluster with the nearest center.

5. Cluster Center Update:

Update the cluster centers as the mean of all points assigned to each cluster.

6. Convergence Criterion:

Iterate the process until the cluster centers stabilize or the maximum number of iterations is reached.

7.Visualization:

Visualize the initial data points, initial cluster centers, and final cluster centers.
Use color coding to differentiate between clusters.
