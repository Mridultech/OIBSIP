# Iris Flower Classification using KNN

A machine learning project that classifies Iris flower species using a K-Nearest Neighbors classifier, demonstrating end-to-end ML workflow from EDA to evaluation.

## Problem Statement
The objective of this project is to classify Iris flowers into Setosa, Versicolor, and Virginica based on physical measurements using supervised learning.

## Dataset Overview
- Dataset: Iris Flower Dataset
- Samples: 150
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width
- Target: Flower Species
- Data Quality: Clean, balanced, no missing values

## Key Insights from EDA
- Petal length and petal width show strong class separability.
- Setosa forms a completely isolated cluster.
- Sepal features exhibit significant overlap and are less discriminative.

## Model Selection
K-Nearest Neighbors (KNN) was chosen due to the cluster-like structure observed in the data. 
Feature scaling was applied as KNN relies on distance-based calculations.

## Results
- Accuracy achieved: 100%
- Confusion matrix confirms class-wise consistency.
- Minor divergence observed for higher K values due to decision boundary smoothing.

## Limitations & Future Scope
- Dataset is small and idealized.
- Real-world noise and bias are absent.
- Future work includes testing on larger datasets and comparing with other classifiers.

## How to Run
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the notebook `Iris_Classification.ipynb`

📄 Detailed project report is available in the `report/` directory.
