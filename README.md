# K-means-clustering-algorithm-to-group-customers-of-a-retail-store-based-on-their-purchase-history

This project focuses on performing customer segmentation using KMeans clustering on the Mall Customer dataset. Customer segmentation is the process of dividing a customer base into distinct groups based on specific characteristics. In this project, we segment customers based on their Annual Income and Spending Score.

# Project Overview
The aim of this project is to identify different customer groups to help businesses understand their customer base better. We use KMeans clustering to group customers into 5 clusters and visualize the segmentation results. Additionally, a Power BI dashboard was created to provide further insights into customer behavior.

# Dataset
Mall_Customers.csv: This dataset includes customer information such as:
CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
# Workflow
Data Loading & Exploration:

The dataset is loaded into a Pandas DataFrame, and basic exploration is done to understand its structure, including checking for missing values.
Feature Selection:

We select Annual Income and Spending Score as the key features for clustering.
KMeans Clustering:

KMeans algorithm is used to group the customers into clusters.
The Elbow Method is applied to determine the optimal number of clusters.
Cluster Visualization:

The customer segments are visualized using a 2D scatter plot with different colors representing different clusters.
Power BI Dashboard:

A Power BI dashboard was created to provide interactive insights into customer segmentation, including charts showing income distribution, spending patterns, and customer demographics.
# Visualization
The clusters were visualized using Matplotlib, where each customer group was color-coded:

Cluster 1 (Green): Represents one segment of customers.
Cluster 2 (Red): Represents another segment.
Cluster 3 (Yellow): Represents another segment.
Cluster 4 (Blue): Represents another segment.
Cluster 5 (Orange): Represents another segment.
The centroids of these clusters were also marked on the plot.

# Power BI Dashboard
The Power BI dashboard created for this project provides detailed insights into the segmented customer data. Key elements of the dashboard include:

Annual income distribution across customer segments.
Spending scores and their correlation with income.
Customer demographics based on gender and age.

# Technologies Used
Python (for KMeans clustering and visualization):
Pandas
Matplotlib
Seaborn
Scikit-learn
Power BI:
Used for data visualization and creating an interactive dashboard

# Results
After running the clustering algorithm, the customers were divided into 5 distinct groups, each representing different purchasing behaviors based on income and spending score. These clusters can be used by the business to tailor marketing strategies, customer engagement, and product offerings.

# License
This project is open-source and available under the MIT License.

