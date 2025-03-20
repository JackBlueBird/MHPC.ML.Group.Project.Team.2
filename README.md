# MHPC.ML.Group.Project.Team.2
Repository for final assignment of course P2.7_ML_intro_24_25, Student Team number 2


## Tasks

1. Data Pre-Processing & Regression Pipeline

    Load the data from the .npy and information files.
    Implement the NaN handling (median replacement) for each spectrum.
    Perform exploratory data analysis by plotting random spectra.
    Set up the regression task:
        Filter for valid fe_h labels.
        Split the data into training and testing sets.
        Train and tune the RandomForestRegressor, LinearRegression, and KNeighborsRegressor.
        Plot the true vs. predicted values.
        Summarize the MSE results in a table.

2. Dimensionality Reduction and Visualization

    Apply PCA to the spectra_withgalah dataset:
        Plot the explained variance ratio.
        Generate scatter plots of PCA-transformed data (e.g. components 0/1, 0/2).
        Reconstruct and plot the first 3 PCA components in the original spectra space.
    Repeat the PCA analysis on the spectraNOgal dataset and compare the results.
    (Optional) Explore additional techniques like t-SNE or UMAP if time permits.

3. Clustering & Anomaly Detection

    Using the PCA-reduced space from spectraNOgal:
        Run a clustering algorithm (e.g. K-Means or DBSCAN).
        For each cluster, compute and plot the average spectrum.
    Implement anomaly detection using IsolationForest on the high-dimensional spectraNOgal data:
        Identify the 5 most anomalous spectra.
        Overlay these anomalies on the PCA scatter plot.
        Plot the individual anomalous spectra and provide observations.
