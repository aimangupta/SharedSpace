# SharedSpace Clustering Analysis Project

## Overview

This project aims to analyze the preferences of 1800 students using various clustering algorithms. The dataset contains integer values ranging from 1 to 5, which represent answers to questions that gauge students' likes and dislikes for different things. The project explores multiple clustering algorithms, including K-modes, K-medoids, DBSCAN, Agglomerative Clustering, Gaussian Mixture Models, Spectral Clustering, Kernel K-means, and RAPIDS analysis for efficient GPU-accelerated computations.

## Dataset

- **Number of Samples:** ~1000 students
- **Features:** Integer values ranging from 1 to 5, representing answers to various questions representing interests of students ranging from their interests in music, movies and shows to their outlook towards life.

## Clustering Algorithms

### 1. K-modes
K-modes is used for clustering categorical data by matching modes (frequent values) instead of means.

### 2. K-medoids
K-medoids is similar to K-means but chooses actual data points as cluster centers (medoids).

### 3. Agglomerative Clustering
Agglomerative Clustering builds nested clusters by merging or splitting them successively.

### 4. Gaussian Mixture Models (GMM)
GMM assumes that the data is generated from a mixture of several Gaussian distributions.

### 5. Spectral Clustering
Spectral Clustering uses the eigenvalues of the similarity matrix of the data to perform dimensionality reduction before clustering.

### 6. Kernel K-means
Kernel K-means applies the kernel trick to map the data into a higher-dimensional space before performing K-means clustering.

## RAPIDS Analysis

RAPIDS provides GPU-accelerated implementations of various machine learning algorithms, including clustering, to speed up computations significantly.

### Installing RAPIDS
Follow the instructions on the [RAPIDS AI GitHub](https://github.com/rapidsai) to set up RAPIDS on your system.

### Example with cuML's KMeans
RAPIDS offers efficient and scalable clustering methods, such as KMeans, through the cuML library.

## Data Preprocessing

### StandardScaler
Standardize features by removing the mean and scaling to unit variance.

# Conclusion
This project demonstrates the application of various clustering algorithms on a dataset of student preferences. By using both traditional and GPU-accelerated methods (RAPIDS), we can achieve efficient and scalable clustering. Experiment with different parameters and preprocessing techniques to optimize clustering performance for your specific dataset.

# Acknowledgments
### The RAPIDS AI team for providing GPU-accelerated libraries.
### The scikit-learn community for their extensive and well-documented machine learning library.
