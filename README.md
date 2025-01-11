# Ice Cream Clustering Analysis

This project focuses on performing clustering analysis on the Baskin Robbins ice cream dataset to identify unique customer preferences and product groupings. The analysis involves data cleaning, scaling, and clustering using the K-Means algorithm, followed by visualizations and insightful findings.

## Project Overview

The goal of this project is to:
1. Clean and preprocess the dataset by removing unnecessary columns.
2. Scale the data to standardize features for better clustering performance.
3. Determine the optimal number of clusters using techniques like the WSS (Knee Plot) and Silhouette Coefficient.
4. Perform K-Means clustering on the data.
5. Visualize the clustering results to gain insights.
6. Create cluster-specific dataframes to examine the unique characteristics of each cluster.
7. Provide meaningful insights and suggest unique names for each cluster based on their attributes.

## Dataset

The dataset used in this analysis is the **Baskin Robbins Ice Cream** dataset, which contains various features related to ice cream products.

### Key Columns:
- **Flavour:** Ice cream flavor (removed for clustering purpose)
- **Category:** Type of product (removed for clustering purpose)
- Other columns represent features like sugar content, fat content, etc.

## Steps Performed

1. **Data Cleaning**: Removed irrelevant columns such as `Flavour` and `Category`.
2. **Data Scaling**: Normalized the data to standardize the feature range.
3. **Clustering Analysis**:
   - Generated WSS (Knee Plot) and Silhouette Coefficient plot to identify the optimal number of clusters.
   - Performed K-Means clustering with the chosen number of clusters.
4. **Visualization**: Used scatter plots and other visual techniques to illustrate the clustering results.
5. **Insights**: Generated at least 3 insights based on the clustering results, with unique features identified for each cluster.
6. **Cluster Naming**: Suggested meaningful names for each cluster based on the identified characteristics.

## Files

- `baskin_robbins_icecream.csv`: Raw dataset used for the analysis.
- `clustering_analysis.ipynb`: Jupyter notebook containing the complete analysis, including data cleaning, scaling, clustering, and insights.
- `visualizations/`: Folder containing visualizations (if any).

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ice-cream-clustering-analysis.git
