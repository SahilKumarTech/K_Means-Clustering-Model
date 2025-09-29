# K-Means Clustering with Elbow Method Analysis

A comprehensive implementation of K-Means clustering algorithm with elbow method for optimal cluster selection.

## Overview
This project demonstrates the complete workflow of K-Means clustering using Python, including data generation, model training, and optimal cluster selection using the elbow method.

## Features
- Synthetic dataset generation using `make_blobs`
- K-Means clustering implementation
- Elbow method for optimal cluster selection
- Data visualization using matplotlib
- Train-test split for model evaluation

## Technologies Used
- Python 3
- scikit-learn
- matplotlib
- pandas
- numpy

## Dataset
- Generated using `make_blobs` from scikit-learn
- 1000 samples with 3 centers and 2 features
- Random state set to 23 for reproducibility

## Key Steps
1. **Data Generation**: Created synthetic blobs dataset
2. **Data Splitting**: 67-33 train-test split
3. **Elbow Method**: Determined optimal clusters (k=3)
4. **K-Means Clustering**: Applied K-Means with k-means++ initialization
5. **Visualization**: Plotted clusters and elbow curve

## Results
- Optimal number of clusters identified: 3
- Clear separation of clusters in visualization
- Distinct elbow point in WCSS (Within-Cluster Sum of Squares) plot
