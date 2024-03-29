# PCA-
Principal component analysis, or PCA, is a dimensionality reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.
Reducing the number of variables of a data set naturally comes at the expense of accuracy, but the trick in dimensionality reduction is to trade a little accuracy for simplicity. Because smaller data sets are easier to explore and visualize and make analyzing data points much easier and faster for machine learning algorithms without extraneous variables to process.
So, to sum up, the idea of PCA is simple — reduce the number of variables of a data set, while preserving as much information as possible.
Steps Involved in PCA:-
Standardize the range of continuous initial variables
Compute the covariance matrix to identify correlations
Compute the eigenvectors and eigenvalues of the covariance matrix to identify the principal components
Create a feature vector to decide which principal components to keep
Recast the data along the principal components axes
