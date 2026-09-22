# California Housing K-Means Clustering

## Overview

This project applies **K-Means Clustering** to the California Housing Dataset as part of an ITI Machine Learning assignment.

The goal is to explore the dataset, standardize the features, determine the optimal number of clusters, and visualize the resulting clusters.

## Steps

* Load and explore the California Housing Dataset
* Check and clean the data
* Select all features except `MedHouseVal`
* Standardize the features using `StandardScaler`
* Determine the optimal number of clusters using:

  * Elbow Method
  * Silhouette Analysis
* Apply K-Means Clustering
* Visualize the clusters using PCA

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

The dataset is loaded directly using Scikit-learn's `fetch_california_housing()` function.

## Project Type

**Unsupervised Learning — Clustering**
