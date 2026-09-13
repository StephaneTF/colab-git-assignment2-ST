# Assignment 9 – Wine Clustering Analysis

This project uses the Wine dataset to group wines with K-means and Hierarchical clustering and visualize their 13 numerical features in two dimensions using PCA.

The notebook includes missing-value checks, feature standardization, cluster selection, visualization, and evaluation using silhouette scores. K-means scored **0.2849**, slightly higher than Hierarchical clustering at **0.2774**.

## Running the Notebook

Open the notebook in Google Colab, upload `wine.data` to the Files panel, and run all cells from top to bottom, starting with the code that adds column names and creates `wine.csv`.

The notebook uses pandas, Matplotlib, and scikit-learn. The original wine class labels are excluded from clustering and PCA and are used only for comparison.
