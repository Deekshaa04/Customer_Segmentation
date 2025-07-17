# Customer Segmentation using K-Means Clustering

This project performs customer segmentation using K-Means Clustering on a mall customer dataset. The goal is to identify distinct groups of customers based on their demographics and spending behavior to assist in targeted marketing strategies.

##  Overview

- **Tool Used**: Google Colab (Python)
- **Dataset Size**: (200, 5) — 200 customers with 5 features
- **Algorithm**: Unsupervised Machine Learning using K-Means Clustering
- **Objective**: Segment customers based on features like Age, Annual Income, and Spending Score

## Dataset Description

The dataset contains the following columns:

| Column           | Description                      |
|------------------|----------------------------------|
| CustomerID       | Unique ID for each customer      |
| Gender           | Gender of the customer           |
| Age              | Age of the customer              |
| Annual Income(k$)| Annual income in thousand dollars|
| Spending Score   | Score assigned based on behavior |

##  Steps Involved

1. **Importing Libraries & Data**
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing distributions and pairplots
   - Identifying outliers and trends
3. **Data Preprocessing**:
   - Handling missing values (if any)
   - Encoding categorical features
   - Feature scaling
4. **Finding Optimal Clusters**:
   - Elbow Method
   
5. **Model Training**:
   - Applying K-Means Clustering
   - Assigning Cluster Labels
6. **Visualization**:
   - 2D cluster plots
   - Interpretation of clusters

##  Results

- Identified **distinct customer segments** that could be used for personalized targeting.
- Found optimal number of clusters (5) using the Elbow Method.

## Key Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
