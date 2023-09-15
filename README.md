# Cryptocurrency Market Analysis Using K-Means Clustering

## Project Overview
This project aims to predict whether cryptocurrencies are affected by 24-hour or 7-day price changes.

## Data Source
The data used in this project is sourced from a CSV file named `crypto_market_data.csv` contained in the `Resources` folder.

## Dependencies

- pandas
- hvplot
- scikit-learn

## Steps

1. **Data Preprocessing**:
   - Load the dataset.
   - Generate a summary statistics
   - Normalize the data using `StandardScaler`.

2. **Elbow Curve Analysis on the Original Scaled Data**:
   - Use the elbow method to determine the optimal number of clusters (k) for K-Means clustering.
   - Plot the inertia values for different k values.

3. **Cluster Analysis on the Original Scaled Data**:
   - Apply K-Means clustering using the optimal k value.
   - Analyze and visualize the clusters to identify patterns.   

4. **Optimize Clusters using PCA**:
   - Apply PCA to reduce the data to three principal components.

5. **Elbow Curve Analysis on the PCA Data**: 
   - Use the elbow method to determine the optimal number of clusters (k) for K-Means clustering on the PCA data.
   - Plot the inertia values for different k values.
 
6. **Cluster Analysis on the PCA Data**:
   - Apply K-Means clustering using the optimal k value.
   - Analyze and visualize the clusters to identify patterns.   

7. **Visualize and Compare the Results**:
   - create a composite plot using hvplot to compare the elbow curve created from the original and PCA Data.
   - create a composite plot using hvplot to compare the crypotocurrency clusyers created from the original and PCA Data.