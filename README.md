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

## Data Analysis and Visualization
   - Exploratory Data Analysis (EDA): Performed distribution analysis of age, annual income, and spending scores using histograms and density plots.
   -  Gender Distribution: Visualized the gender distribution using a pie chart.
   - Correlation Analysis: Used a heatmap to display the correlation between numerical features.
   - Pairwise Relationships: Examined relationships between age, annual income, and spending score using pair plots.


##K-Means Clustering
   - Optimal Number of Clusters: Determined the optimal number of clusters using the Elbow method.
   - Clustering: Applied K-Means clustering to group customers into five clusters based on their annual income and spending score.
   - Visualization: Plotted the clusters and their centroids to visualize the segmentation results.


## Results

- **Clusters**: Identified five distinct customer clusters based on annual income and spending score.
- **Centroids**: Visualized the centroids to represent the average profile of each cluster.

## Usage

1. Clone the repository.
2. Install the necessary libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`.
3. Run the notebook `Mall_Customer_Segmentation_Analysis.ipynb` to perform data analysis and clustering.

## Files

- `Mall_Customers.csv`: The dataset used for clustering.
- `Mall_Customer_Segmentation_Analysis.ipynb`: Colab notebook with code and analysis.


