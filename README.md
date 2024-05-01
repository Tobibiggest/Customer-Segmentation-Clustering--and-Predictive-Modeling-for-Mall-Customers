
Project Overview:

Title: Customer Segmentation and Predictive Modeling for Mall Customers

Objective:
The goal of this project is to perform customer segmentation using hierarchical and k-means clustering methods on the Mall_Customers dataset, focusing on the columns Age, Income, and Spend_Score. Following clustering, we aim to profile the clusters using ANOVA analysis to identify significant differences among them. Additionally, we will build a predictive model to forecast Spend_Score based on customer attributes.

Data Description
We have a dataset called “Mall_Customers.xls” containing information about mall customers. The relevant columns are as follows:

Customer ID: A unique identifier for each customer.
Gender: The gender of the customer (male or female).
Age: The age of the customer.
Annual Income: The annual income of the customer in thousands of dollars.
Spending Score: A score assigned by the mall based on customer behavior and spending nature.
Step 1: Data Exploration and Preprocessing
Load the dataset and explore its structure.
Check for missing values and outliers.
Encode the gender column (if necessary).
Step 2: Clustering
Hierarchical Clustering
Apply hierarchical clustering to group customers based on their features (Age, Income, and Spending Score).
Determine the optimal number of clusters using techniques like dendrogram analysis or silhouette score.
K-Means Clustering
Use K-means clustering to create clusters.
Choose the appropriate number of clusters (K) using the elbow method or silhouette score.
Assign each customer to a cluster based on their features.
Step 3: Profiling Clusters
Profile each cluster by analyzing the average values of Age, Income, and Spending Score within each cluster.
Visualize the clusters using scatter plots or other relevant plots.
Step 4: ANOVA or Multinomial Logistic Regression
To understand what truly differentiates the clusters, perform either of the following:
ANOVA (Analysis of Variance): Compare the means of Age, Income, and Spending Score across clusters. If significant differences exist, these variables contribute to cluster separation.
Multinomial Logistic Regression: Use this method if the clusters are categorical. It will help identify which features significantly influence cluster membership.
Step 5: Descriptive Summary of Clusters
Write a brief summary for each cluster:
Describe the characteristics of customers in each cluster (e.g., “High-income, young spenders” or “Middle-aged moderate spenders”).
Highlight the key features that differentiate the clusters.
Step 6: Predictive Modeling
Use the Spending Score as the target variable.
Split the data into training and testing sets.
Build predictive models using:
Linear Regression
Support Vector Machine (SVM)
Neural Networks (NN)
ElasticNet Regression
and 
GridSearch for HyperParameter settings
Conclusion
In this project, we explored customer segmentation using clustering techniques, profiled the clusters, and investigated the factors that differentiate them. Although the preferred evaluation metric was not reached, we proceeded with SVM, Neural Networks, and ElasticNet to build a predictive model for Spending Score.
