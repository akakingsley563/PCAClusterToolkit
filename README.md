# PCAClusterToolkit


![image](https://github.com/akakingsley563/PCAClusterToolkit/assets/130521961/d9df0f49-e984-4527-b496-d57302ba684e)





## Table of Contents
- [Project Overview](#project-overview)
- [Project Aims](#project-aims)
- [Project Objectives](#project-objectives)
- [Data Preprocessing](#data-preprocessing)
- [Model Used](#model-used)
- [Key Insights](#key-insights)
- [Conclusion](#Conclusion)

## Project Overview
The project involves the application of machine learning techniques, specifically clustering and principal component analysis (PCA), to a dataset. The tasks include cleaning and preprocessing the data, implementing K-Means and Hierarchical clustering methods, and determining the optimal number of clusters. Additionally, PCA is used to reduce the dataset to its principal components for visualization and analysis.

## Project Aims and Objectives

## Data Cleaning and Preprocessing:
- Handle missing values in the dataset.
- Standardize the dataset for clustering and PCA.
  
## Clustering Analysis:
- Apply K-Means and Hierarchical clustering methods to the dataset.
- Determine the optimal number of clusters using the Elbow method and Silhouette scores.
  
## Dimensionality Reduction:
- Implement PCA to reduce the dataset to two principal components.
- Visualize the clusters in the reduced dimensional space.

## Data Processing
- Importing Libraries and Dataset: Libraries such as Pandas, NumPy, and Scikit-learn were used for data manipulation and modeling. The dataset was loaded and basic exploratory data analysis was performed.
- Data Cleaning: Missing values were identified and handled. Non-numeric columns were encoded for clustering analysis.
- Standardization: Features were standardized to ensure that each feature contributes equally to the distance calculations in clustering.
-  Clustering Implementation: Both K-Means and Hierarchical clustering were applied. The Elbow method and Silhouette scores were used to find the optimal number of clusters.
- PCA: The dataset was reduced to two principal components, and a scatter plot was created to visualize the clusters.


## Model Used
- K-Means Clustering: This algorithm partitions the dataset into K distinct clusters based on feature similarities. The optimal number of clusters is determined using the Elbow method.
- Hierarchical Clustering: This method builds a hierarchy of clusters and was used to supplement the K-Means results. The optimal number of clusters was also validated using Silhouette scores.

## Key Insights
- Data Preparation: Standardizing data is essential for accurate clustering. Handling missing values and ensuring the dataset is clean improves model performance.
- Optimal Clustering: The Elbow method and Silhouette scores are effective for determining the optimal number of clusters. For this dataset, both methods suggested 3 as the optimal number of clusters.
- PCA Visualization: Reducing dimensions with PCA helps in visualizing the separation of clusters, providing a clearer understanding of the data structure.
