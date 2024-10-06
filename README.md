# HIERARCHICAL-CLUSTERING

- performed hierarchical agglomerative clustering on socioeconomic data from various countries. This
clustering will allow us to visualize which countries have similar socioeconomic
situations.
- Processed real-world data
-  Visualized the clustering process

## building process
- loaded dataset(it contained 8 columns with first column not having any name) and created a list of dictionaries(the list contains N dictionaries each containing 8 elements, so N feature vectors of M features each)
- calculated features and filtered 2 columns not needed for the processing(they are country name and indexing, the column above discussed without a name). Returned a numpy array of shape (6,2) and dtype float64.
