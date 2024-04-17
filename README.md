# Clustering_the_Countries

Clustering_the_Countries is a data science project focused on clustering countries based on socio-economic and health factors to prioritize aid allocation. By analyzing indicators such as GDP per capita, income, and child mortality rates, the project aims to identify countries that are in the greatest need of financial assistance.

## Introduction

Non-governmental organizations (NGOs) and international aid agencies often struggle to allocate resources effectively to countries in need. With limited funds, it's essential to prioritize aid to regions where it can have the most significant impact. Clustering_the_Countries addresses this challenge by utilizing data science techniques to identify and categorize countries based on their level of need.

## Key Points

- **Data Exploration and Preparation**: The project begins by importing necessary libraries, reading the data, and performing initial data exploration, including checking for missing values and data types. Some columns are converted to their actual values based on percentages.

- **Data Visualization**: Visualizations like pair plots, heatmaps, and box plots help understand the relationships between different features and identify potential outliers.

- **Handling Outliers**: A method of flooring and capping is used to handle outliers, ensuring that the dataset remains suitable for analysis.

- **Clustering Suitability**: A Hopkins test is performed to assess the clustering tendency of the dataset, indicating a high tendency to cluster.

- **Scaling the Data**: Before applying clustering algorithms, the features are standardized using StandardScaler.

- **Clustering Algorithms**: Both K-means and Hierarchical Clustering are applied, with K=3 chosen based on the elbow method and silhouette score. Hierarchical Clustering is preferred for its interpretability.

- **Cluster Profiling**: Box plots are used to visualize the distribution of important features across clusters, helping differentiate between developed and underdeveloped countries.

- **Visualizing Clusters**: Scatter plots are utilized to visualize relationships between important features and cluster assignments.

- **Final Analysis and Recommendations**: Based on cluster analysis, underdeveloped countries in dire need of aid are identified, considering factors like low GDP per capita, low income, and high child mortality rates.

- **Conclusion**: Hierarchical Clustering is chosen as the final model due to its interpretability and lack of requirement for specifying the number of clusters in advance.

## How to Use

Follow these steps to use the project:

1. Clone the repository:

```bash

