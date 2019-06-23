This folder contains implementation of dimensionality reduction using PCA. Usually, PCA,like any other Machine Learning model could be directly imported through sklearn, but it is very important to understand the math behind it, so this python script has all the math involved in PCA

It is basically 3 steps:
1. Eigen Decomposition on the Covariance Matrix
2. Sort the Eigen Values, for obtaining PCA
3. Projection Matrix to get the new feature space

