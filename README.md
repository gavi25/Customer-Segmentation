# Customer-Segmentation

# Customer Segmentation Using K-Means Clustering

## Overview

This project focuses on segmenting customers of a retail mall using the K-Means clustering algorithm. The primary goal is to analyze customer behavior based on their annual income and spending score to create distinct customer profiles. This segmentation helps in crafting targeted marketing strategies and improving customer engagement.

## Dataset

The dataset includes information on approximately 200 active customers with the following attributes:
- **CustomerID**: Unique identifier for the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income in thousands of dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Steps & Analysis

1. **Data Exploration**:
   - Distribution analysis of age, annual income, and spending score.
   - Gender distribution and correlation analysis.

2. **Visualization**:
   - Histograms, density plots, and pair plots to understand data distribution and relationships.
   - Scatter plots to visualize the relationship between age, annual income, and spending score.

3. **Clustering**:
   - Applied K-Means clustering to segment customers into 5 clusters.
   - Used the Elbow method to determine the optimal number of clusters.
   - Visualized clusters and centroids to understand the segmentation results.

## Results

- **Clusters**: Identified five distinct customer clusters based on annual income and spending score.
- **Centroids**: Visualized the centroids to represent the average profile of each cluster.

## Usage

1. Clone the repository.
2. Install the necessary libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`.
3. Run the notebook `Mall_Customer_Segmentation_Analysis.ipynb` to perform data analysis and clustering.

## Files

- `Mall_Customers.csv`: The dataset used for clustering.
- `Customer_Segmentation.ipynb`: Jupyter notebook with code and analysis.


