
# Principal Component Analysis (PCA) on Health and Economic Data

This repository contains a Python-based implementation of **Principal Component Analysis (PCA)** to analyze and visualize multidimensional datasets related to global health and economic indicators.

## Project Overview

The goal of this project is to reduce the dimensionality of complex socioeconomic data while retaining as much variance as possible. This allows for better visualization of patterns, such as identifying clusters of countries with similar development profiles or health outcomes.

##  Repository Structure

* `code9.ipynb`: The main Jupyter Notebook containing the data preprocessing, exploratory data analysis (EDA), PCA implementation, and visualization.
* `health data.csv`: Dataset containing health-related metrics (e.g., life expectancy, child mortality, health spending).
* `econ data2.csv`: Dataset containing economic indicators (e.g., GDP per capita, inflation, income).

## Analysis Steps

1. **Data Preprocessing**: Handling missing values and scaling features (Standardization) to ensure all variables contribute equally to the components.
2. **PCA Implementation**:
* Calculating the covariance matrix.
* Determining Eigenvalues and Eigenvectors.
* Analyzing the **Explained Variance Ratio** to decide the optimal number of components.


3. **Visualization**:
* Scree plots to visualize variance.
* 2D/3D Scatter plots of the principal components to identify clusters or outliers.

## Requirements

To run the notebook, you will need the following Python libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`

## Key Insights

The PCA helps in identifying which variables (like GDP or Life Expectancy) are the strongest drivers of difference between the observations in the datasets. It simplifies high-dimensional data into a few "Principal Components" that can be used for further machine learning tasks like K-Means Clustering.

---

### How to use:

1. Clone the repository:
```bash
git clone https://github.com/agatazz/PCA.git

```
2. Open `code9.ipynb` in Jupyter Notebook or Google Colab.
3. Ensure the `.csv` files are in the same directory as the notebook.
