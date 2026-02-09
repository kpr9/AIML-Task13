# PCA – Dimensionality Reduction using MNIST / Digits Dataset
# Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
# Dataset
- MNIST Dataset
# Steps
- Loaded MNIST / Digits dataset
- Flattened images into feature vectors
- Applied StandardScaler for proper PCA performance
- Applied PCA with different component counts (2, 10, 30, 50)
- Tracked explained variance ratio for each PCA configuration
- Plotted cumulative explained variance to select optimal components
- Transformed dataset into reduced dimensional space
- Trained Logistic Regression on both original and reduced datasets
- Compared accuracy of original vs reduced model
- Visualized PCA 2D scatter plot for class separation
# Model Used
- Principal Component Analysis (PCA) for dimensionality reduction
- Logistic Regression for classification comparison
# Outcome
- Understood feature compression and variance trade-off.
- Learned how dimensionality reduction improves model efficiency.
- Gained hands-on experience with variance-based feature extraction.
