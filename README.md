# Lesson 9 – Unsupervised Learning Using the Iris Dataset

## Project Overview

This project demonstrates the application of unsupervised machine learning techniques using the Iris dataset.

The project includes:

- Data preprocessing
- Missing value detection
- Duplicate removal
- Feature scaling using StandardScaler
- K-Means Clustering
- Hierarchical Clustering
- Principal Component Analysis (PCA)
- Model evaluation using the Silhouette Score
- Deployment and monitoring strategy

## Dataset

The Iris dataset contains measurements of iris flowers using four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

After preprocessing, one duplicate record was removed, leaving 149 observations.

## Models Implemented

### K-Means Clustering

- Optimal number of clusters determined using the Elbow Method
- Silhouette Score: **0.461**

### Hierarchical Clustering

- Ward linkage method
- Silhouette Score: **0.450**

## Results

K-Means slightly outperformed Hierarchical Clustering, producing better-defined clusters on the Iris dataset.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Files

- `Lesson_9_Unsupervised_Learning_Assignment.ipynb`
- `README.md`

## Author

Josee Uwamariya
