# Customer-Segmentation-and-Behavior-Analysis-using-Clustering
This repository contains a project on customer segmentation and behavior analysis using clustering techniques, specifically K-Means clustering. The objective is to segment customers based on their shopping behavior and demographics to identify distinct groups for targeted marketing strategies.

#Dataset Overview
The dataset includes the following features:
customer_id: Unique identifier for each customer
age: Age of the customer
gender: Gender of the customer
category: Category of the product purchased
quantity: Quantity of the product purchased
price: Price of the product purchased

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic statistics, including data types and missing values.
Exploratory Data Analysis (EDA):
Visualize the distribution of customer ages.
Plot the relationship between quantity purchased and price.
Analyze price distribution by product category.
Data Preprocessing:
Aggregate data by customer to get the mean age, total quantity purchased, and total price spent per customer.
Normalize the features using StandardScaler.
Clustering with K-Means:
Use the Elbow Method to determine the optimal number of clusters.
Fit the K-Means model with the chosen number of clusters.
Assign cluster labels to each customer.
Cluster Analysis:
Calculate the mean values of numeric features for each cluster.
Display the count of customers in each cluster.
Cluster Visualization:
Reduce the dimensionality of the data using PCA for visualization.
Plot the clusters in a 2D scatter plot to visualize the segmentation.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
