# Wholesale-Customer-Segmentation-Analysis
# Wholesale Customer Segmentation Analysis

This repository focuses on the analysis and segmentation of clients of a wholesale distributor based on their annual spending on diverse product categories. The dataset provides insights into the different types of customers that the distributor interacts with.


## Task

The primary goal of this project is to best describe the variation in the different types of customers that a wholesale distributor deals with. The project involves the following implementation steps:

### Key Tasks

1. **Exploratory Data Analysis (EDA):** 
   - Explore the dataset and perform any necessary data cleaning.
   
2. **Feature Scaling:** 
   - Implement feature scaling to normalize the data.
   - Compare the effects of MinMaxScaler and StandardScaler using histograms/KDE.
   - Choose one scaler and provide reasoning for the selection.

3. **Feature Selection:** 
   - Find the optimal number of features using Recursive Feature Elimination with Cross-Validation (RFECV).
   - Display a plot showing the relationship between the number of selected features and cross-validation score, using 'channel' as the target variable.

4. **K-Means Clustering:** 
   - Implement K-Means Clustering for K values ranging from 2 to 15.
   - Identify the optimum number of clusters using the elbow method.

5. **Principal Component Analysis (PCA):** 
   - Implement PCA to reduce the dimensionality of the data.
   - Calculate and visualize the variance explained by the first 2 and first 4 components.
   - Visualize the clusters in the data using PCA.

6. **XGBoost Classifier:** 
   - Implement an XGBoost Classifier with 5-fold cross-validation.
   - Report performance metrics.
