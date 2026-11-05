# Fast-Food Nutrition Clustering Using Machine Learning

## Project Overview

This project explores nutritional patterns in fast-food menu items using unsupervised machine learning. The goal is to compare different clustering algorithms, identify similarities between food items, and analyze nutritional characteristics across the resulting clusters.

Six clustering algorithms are implemented and evaluated to determine how effectively they group food items based on nutritional information.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Google Colab / Jupyter Notebook

## Clustering Algorithms

The project compares six unsupervised machine learning algorithms:

1. **K-Means:** Groups data into a predefined number of clusters.
2. **Agglomerative Clustering:** Uses hierarchical clustering to group similar observations.
3. **Gaussian Mixture Model (GMM):** Uses probabilistic modeling to identify clusters.
4. **DBSCAN:** Identifies density-based clusters and potential noise points.
5. **Spectral Clustering:** Uses similarities between observations to form clusters.
6. **Mean Shift:** Identifies clusters based on areas of high data density.

## Methodology

The analysis follows these steps:

1. Load the fast-food nutrition dataset.
2. Clean the data and handle missing values.
3. Standardize numerical features using StandardScaler.
4. Apply six clustering algorithms.
5. Evaluate clustering quality using Silhouette Scores.
6. Compare cluster counts, noise points, and average calories.
7. Visualize clustering results using PCA and comparison charts.
8. Analyze nutritional characteristics of the selected clustering model.

## Model Evaluation

The primary evaluation metric is the **Silhouette Score**, which measures how well observations fit within their assigned clusters compared with other clusters.

Higher scores generally indicate better-separated clusters.

The notebook also includes a normalized silhouette-score percentage for visualization. This percentage is not classification accuracy.

## Nutritional Analysis

The project examines nutrients such as protein, fiber, calcium, vitamins, sugar, calories, fat, sodium, and cholesterol.

A custom exploratory health score is used to compare nutritional characteristics across clusters.

This score is a project-specific analytical measure rather than a medically validated nutritional rating.

## Visualizations

The notebook includes:

- Silhouette Score comparison bar chart
- PCA cluster visualizations
- Algorithm comparison table
- Normalized score pie chart
- Comparison heatmap

## How to Run

1. Download or open the Jupyter Notebook in Google Colab.
2. Install any required Python libraries.
3. Run the notebook.
4. Upload the fast-food nutrition dataset when prompted.
5. Review the clustering results and visualizations.

## Project Purpose

This project demonstrates practical experience with data preprocessing, unsupervised machine learning, model evaluation, and exploratory data analysis.

It also illustrates how machine learning can be used to investigate patterns in real-world nutritional datasets.

## Author

**Lorena Ramirez**  
Computer Science Student | Kean University
