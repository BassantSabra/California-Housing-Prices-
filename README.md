
# California Housing Prices Analysis

This Jupyter Notebook provides an analysis of the California housing prices dataset. The analysis includes data preprocessing, normalization, K-means clustering, and visualization of the results.

## Dataset

The dataset used in this analysis includes information about housing prices in various regions of California. Key features of the dataset are:

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Median House Value

## Analysis

The notebook performs the following steps:

1. **Data Loading and Preprocessing**: The dataset is loaded and basic preprocessing is done, including handling missing values and normalization of the features.

2. **Normalization**: The features `longitude` and `latitude` are normalized to ensure they fit well into the K-means model.

3. **K-means Clustering**: K-means clustering is applied to the normalized data to identify distinct clusters based on geographical locations.

4. **Visualization**: The clusters are visualized using scatter plots and box plots to show the distribution of median house prices within each cluster.

## Results

- The northern and central clusters (clusters 0 and 1) have higher median house values compared to the southern cluster (cluster 2).
- Normalization plays a crucial role in ensuring effective clustering.
- A higher value of `k` (more than 3) may provide more efficient clustering.

