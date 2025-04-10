# Mall Customer Clustering

This project uses unsupervised learning techniques to segment mall customers based on demographic and behavioral data. By applying clustering algorithms, the analysis aims to uncover distinct customer groups that can be used for targeted marketing, personalized offers, and improving customer experience.

## Project Overview

Mall customer segmentation is a valuable strategy for businesses looking to better understand and serve their clientele. This project demonstrates how to:
- Load and explore customer data.
- Clean and preprocess the data.
- Apply clustering algorithms like **K-Means** and **Agglomerative Clustering**.
- Evaluate clusters using measures such as the silhouette score.
- Visualize the segmentation results to drive actionable business insights.

## Dataset

The analysis uses the `Mall_Customers.csv` dataset, which includes the following key attributes:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Categorical variable representing the customer's gender.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Yearly income of the customer (in thousands of dollars).
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending habits.


## Methods

### 1. Data Exploration and Preprocessing

- **Exploration:** Initial inspection of data types, summary statistics, and distribution analysis.
- **Cleaning:** Handling of missing values and encoding categorical variables (e.g., converting "Gender" to numerical format).
- **Scaling:** Standardization of numeric features to ensure uniformity during clustering.

### 2. Clustering Techniques

- **K-Means Clustering:** Uses the elbow method to determine the optimal number of clusters, followed by fitting the model and interpreting the results.
- **Agglomerative Clustering:** Builds a dendrogram to provide a hierarchical view of clusters, allowing for a deeper understanding of the customer segmentation structure.

### 3. Evaluation

- **Silhouette Score:** Quantitatively evaluates the quality of the clusters.
- **Visualization:** Generates scatter plots and dendrograms to visually assess the segmentation
