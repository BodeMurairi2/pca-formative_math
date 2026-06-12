# PCA on African Macroeconomic Data

This project implements Principal Component Analysis (PCA) from scratch using only NumPy, applied to a dataset of macroeconomic indicators (GDP growth, inflation, trade, FDI, etc.) for African countries from 2000-2023.

The notebook (`PCA_Formative_2[Peer_Pair_40].ipynb`) walks through:

1. Loading and cleaning the dataset (handling missing values, dropping sparse features)
2. Standardizing the data
3. Computing the covariance matrix
4. Performing eigendecomposition
5. Sorting principal components by explained variance
6. Projecting the data onto the selected principal components
7. Outputting the reduced dataset
8. Visualizing the data before and after PCA

The goal is to reduce the dimensionality of the dataset while retaining the most informative structure for comparing economic development trajectories across countries.
