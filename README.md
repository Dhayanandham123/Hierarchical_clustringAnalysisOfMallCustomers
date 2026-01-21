# Hierarchical_clustringAnalysisOfMallCustomers
Overview

This project implements hierarchical clustering to analyze and group data based on similarity. Unlike partition-based clustering methods, hierarchical clustering builds a tree-like structure that shows how clusters are formed at different levels. The implementation is done using Python in a Jupyter Notebook for clarity and ease of understanding.

Objectives

To understand the working of hierarchical clustering

To perform clustering without predefining the number of clusters

To visualize cluster formation using dendrograms

To analyze similarity-based grouping in datasets

Technologies Used

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

SciPy

Scikit-learn

Methodology

Data Loading
The dataset is loaded and inspected to understand its structure and features.

Data Preprocessing
Cleaning and normalization are performed to make the data suitable for distance-based clustering.

Distance Calculation
Pairwise distances between data points are computed using standard distance metrics.

Hierarchical Clustering
Agglomerative clustering is applied to progressively merge similar data points.

Dendrogram Visualization
A dendrogram is plotted to visualize the hierarchical structure and decide the number of clusters.

Cluster Formation
Final clusters are created based on the dendrogram cut-off level.

How to Run the Project

Install required libraries:

pip install numpy pandas matplotlib scipy scikit-learn


Open the notebook:

jupyter notebook hierarchical_clustering.ipynb


Run the cells sequentially to view results and visualizations.

Use Cases

Exploratory data analysis

Customer segmentation

Pattern discovery

Academic and learning purposes

Conclusion

This project provides a clear and practical demonstration of hierarchical clustering and its advantages in exploratory analysis. By visualizing the clustering hierarchy, it enables better interpretation of relationships within data and supports informed decision-making when defining clusters.
