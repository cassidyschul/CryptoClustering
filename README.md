# Unsupervised Machine Learning Cryptocurrency Clustering

In this assignment, I developed a Python script using the scikit-learn library to group various cryptocurrencies. Initially, the data was normalized with the StandardScaler module. I then employed the KMeans model and an elbow curve to identify and visualize the optimal k value, grouping the data into four clusters and visualizing two features using the hvPlot library.

Next, I performed Principal Component Analysis (PCA) to reduce the data dimensionality to three components. Using the KMeans model and an elbow curve again, I determined and visualized the optimal k value for the PCA data, grouping it into four clusters and visualizing two features with hvPlot. By comparing the elbow curves and cluster plots, it was evident that while the PCA clustered data incorporated only approximately 90% of the original data, the clusters were more defined.
