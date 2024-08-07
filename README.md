
# PCA and Logistic Regression on Breast Cancer Dataset

This project demonstrates the application of Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for classification using the breast cancer dataset. Below you will find instructions on how to set up, run, and understand the code provided.


## Prerequisites

Ensure you have the following Python packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Dataset

The breast cancer dataset is used in this project and is available directly from the `sklearn.datasets` module. The dataset contains features and labels related to breast cancer diagnosis.

## Script Overview

The main Python script, `pca_logistic_regression.py`, performs the following tasks:

1. **Load and Preprocess Data**
   - Loads the breast cancer dataset.
   - Standardizes the data to have mean 0 and variance 1.

2. **Apply PCA**
   - Reduces the dataset to 2 principal components.
   - Creates a scatter plot to visualize the data in the PCA feature space.

3. **Implement Logistic Regression (Bonus)**
   - Trains a logistic regression model using the PCA-reduced data.
   - Evaluates the model using classification metrics.

