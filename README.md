# K-Means Clustering on Mall Customer Dataset

## Project Overview
This project applies **K-Means Clustering** to segment customers based on purchasing patterns in a mall setting. The main goal is to identify distinct customer groups to enable targeted marketing strategies and enhance customer service. By analyzing spending scores and other key factors, this project helps create valuable customer segments using clustering techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Steps to Follow](#steps-to-follow)
  - [1. Importing Libraries and Dataset](#1-importing-libraries-and-dataset)
  - [2. Data Understanding](#2-data-understanding)
  - [3. Data Preprocessing](#3-data-preprocessing)
  - [4. Determining Optimal Clusters](#4-determining-optimal-clusters)
  - [5. Applying K-Means Clustering](#5-applying-k-means-clustering)
  - [6. Visualizing Clusters](#6-visualizing-clusters)
- [Conclusion](#conclusion)
- [Results](#results)
- [Future Work](#future-work)

---

## Requirements

Before running the code, ensure you have the following libraries installed:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For array operations.
- **Matplotlib/Seaborn**: For visualizing clusters and exploratory analysis.
- **Scikit-learn**: For implementing K-Means clustering.

---

## Steps to Follow

### 1. Importing Libraries and Dataset
Load the required libraries and the mall customer dataset. The dataset includes attributes such as customer age, income, and spending score.

### 2. Data Understanding
Examine the dataset’s structure and check for any missing values or inconsistencies. Analyze key features to understand how they might impact customer segmentation.

### 3. Data Preprocessing
Select relevant features (e.g., Annual Income and Spending Score) and scale them if necessary to ensure clustering accuracy.

### 4. Determining Optimal Clusters
Use the **Elbow Method** to find the optimal number of clusters. Plot the Within-Cluster Sum of Squares (WCSS) against the number of clusters and observe the "elbow point," which indicates the ideal number of clusters.

### 5. Applying K-Means Clustering
Once the optimal number of clusters is determined:
- Initialize and fit the K-Means model.
- Assign each customer to a cluster based on their spending patterns and annual income.

### 6. Visualizing Clusters
Visualize the clustered data by plotting each cluster in different colors. This enables you to interpret and label each segment based on behavior (e.g., High Spenders, Low Spenders).

---

## Conclusion
The **K-Means Clustering** model segmented the customers successfully, providing insights into customer behaviors and spending patterns:
- Number of clusters: **(Optimal Number)**
- Key segments identified include **(e.g., High Income/High Spending, Low Income/Low Spending)**.

---
