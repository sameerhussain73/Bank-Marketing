Bank Marketing Campaign Analysis

Project Description

This repository contains the analysis and predictive modeling of a bank marketing campaign. The goal was to utilize machine learning to predict customer subscription rates to a term deposit, offering insights into customer behavior and effectiveness of the campaign.

Dataset
The dataset used in this project comprises 41,188 instances, each representing a customer and their response to the bank's marketing campaign. It features a mix of customer demographic information, previous campaign outcomes, and economic context variables.

Approach

Data Preprocessing: 
  Implemented one-hot encoding for categorical variables and feature scaling using StandardScaler.
  Exploratory Data Analysis (EDA): Conducted an in-depth EDA to understand the dataset's characteristics, including class distribution and feature correlation.
  KMeans Clustering: Applied unsupervised learning to segment customers into meaningful groups.

Model Evaluation: 
  Assessed the model using accuracy metrics to determine how well the clustering corresponds with the customer subscription status.

Results
  The KMeans clustering algorithm successfully identified distinct customer segments, with an accuracy of approximately 70.33% when one cluster was interpreted as indicating a subscription to the term deposit.
  Insights derived from the analysis provided actionable recommendations for optimizing marketing strategies.

Tools and Technologies
  Python: Programming language used for the entire project.
  Pandas & NumPy: Data manipulation and numerical computation.
  Matplotlib & Seaborn: Data visualization.
  Scikit-learn: Preprocessing, clustering, and model evaluation.

Usage
Instructions for setting up, exploring the dataset, conducting EDA, and running the clustering model are included. Users can replicate the analysis, experiment with different parameters, and extend the model for further insights.
