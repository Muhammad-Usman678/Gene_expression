# GeneCoViz: Interactive Gene Co-expression Network Analysis and Visualization

## Table of Contents
1. [Introduction](#introduction)
2. [Data Loading](#data-loading)
3. [Gene Expression Scatter Plot](#gene-expression-scatter-plot)
4. [K-Means Clustering](#k-means-clustering)
5. [Evaluating Clusters with DBSCAN](#evaluating-clusters-with-dbscan)
6. [Agglomerative Clustering](#agglomerative-clustering)
7. [Clusters Visualization with UMAP and KMeans](#clusters-visualization-with-umap-and-kmeans)
8. [Network with Community Detection](#network-with-community-detection)
9. [Conclusion](#conclusion)
10. [Dependencies](#dependencies)
11. [Usage](#usage)

## Introduction
This project analyzes gene expression data to uncover hidden structures using a variety of clustering techniques and visualization tools. The methods used include K-Means, DBSCAN, and Agglomerative Clustering. Visualization techniques such as UMAP are employed to present the data in a more interpretable form.

## Data Loading
The data loading section covers the steps to import and preprocess the gene expression data required for analysis.

## Gene Expression Scatter Plot
This section includes the creation of scatter plots to visualize the gene expression data. Scatter plots help in understanding the distribution and relationship between different gene expressions.

## K-Means Clustering
K-Means clustering is applied to group the data into clusters based on their gene expression profiles. The results are evaluated to determine the optimal number of clusters.

## Evaluating Clusters with DBSCAN
Density-Based Spatial Clustering of Applications with Noise (DBSCAN) is used to evaluate the clusters formed by K-Means and to identify any noise in the data.

## Agglomerative Clustering
Agglomerative clustering, a hierarchical clustering method, is applied to further analyze the gene expression data. This method builds a hierarchy of clusters for better insights.

## Clusters Visualization with UMAP and KMeans
UMAP (Uniform Manifold Approximation and Projection) is used alongside K-Means clustering for visualization. UMAP helps in reducing the dimensionality of the data, making it easier to visualize the clusters.

## Network with Community Detection
This section involves creating a network from the gene expression data and applying community detection algorithms to identify tightly-knit groups within the network.

## Conclusion
The conclusion summarizes the findings from the various clustering techniques and visualizations, providing insights into the gene expression data.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- UMAP
- NetworkX

## Usage
To run the analysis, execute the Jupyter notebook `GeneCoViz.ipynb` in a suitable environment with the necessary dependencies installed.
