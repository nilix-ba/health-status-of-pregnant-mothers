# Health Status of Pregnant Mothers

## Dataset Description

The dataset related to the health status of pregnant mothers is available [here](https://archive.ics.uci.edu/ml/datasets/Maternal+Health+Risk+Data+Set). This data contains 1014 samples with 7 columns. The goal of this project is to perform classification on this data to divide it into three classes: mid-risk, low-risk, and high-risk.

## Project Description

The project uses Python for data preprocessing, feature selection, and classification. It covers the following main steps:

1. Data loading and exploration.
2. Data preprocessing, including converting categorical data to numeric, handling missing values, and normalizing the dataset.
3. Outlier removal using Z-score.
4. Feature selection and multicollinearity analysis using Variance Inflation Factor (VIF).
5. Model selection and evaluation using four classifiers: Decision Tree, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest.
6. Cross-validation for model evaluation.
7. Visualization of feature relationships using scatter plots.

The project provides insights into the health status classification of pregnant mothers and identifies the most suitable classification model for this task.
