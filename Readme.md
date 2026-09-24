# Customer Segmentation: RFM Clustering

Customer segmentation on the Online Retail dataset using RFM features, K-Means and Gaussian Mixture Models (GMM).

## Files

- `CG_C08_M07.ipynb`: analysis notebook
- `OnlineRetail.csv`: transaction data (place in the same folder as the notebook)

## Approach

1. Build Recency, Frequency and Monetary (RFM) features per customer and standardize them
2. Choose the number of clusters with the elbow method (K-Means) and BIC/AIC (GMM)
3. Fit K-Means and GMM with 3 clusters and compare them using silhouette scores
4. Visualize both clusterings side by side in 2D with PCA

## Results

- 4,371 customers segmented
- Silhouette score (3 clusters): K-Means 0.5719, GMM 0.1872