# CryptoClustering

This project uses machine learning techniques to cluster cryptocurrencies based on their market behavior and performance. By leveraging K-Means clustering and Principal Component Analysis (PCA), the notebook explores methods to identify patterns and optimize the clustering process.

---

## Features

1. **Data Preparation**:
   - The dataset is loaded and preprocessed to include relevant features for clustering

2. **K-Means Clustering**:
   - Clustering is applied using the original scaled data
   - The best value for `k` is determined using the elbow method

3. **Principal Component Analysis (PCA)**:
   - PCA is used to reduce dimensionality, retaining 89.50% of the total variance
   - Optimized clusters are created using the PCA-transformed data

4. **Cluster Visualization**:
   - Results from clustering the original data and PCA-transformed data are visualized and compared

---

## Libraries Used

The following Python libraries are used in the notebook:
- **Pandas**: For data manipulation and preprocessing
- **hvplot.pandas**: For interactive visualization of clustering results

---

## Key Steps and Insights

### Prepare the Data
- The cryptocurrency data is preprocessed, scaled, and analyzed for clustering

### Find the Best Value for `k`
- **Question**: What is the best value for `k`?
- **Answer**: The best value for `k` is 4, as determined by the elbow method

### Cluster Cryptocurrencies with K-Means
- Clustering is performed on the original scaled data using the K-Means algorithm

### Optimize Clusters with PCA
**Question**: What is the total explained variance of the three principal components?
  
**Answer**: The total explained variance is 89.50%.

PCA reduces the dataset to three principal components, optimizing clustering results.

### Compare Results
After visually analyzing the results, it is observed that reducing features using PCA leads to more compact clusters, thus categorizing data more accurately

