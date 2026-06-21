# Music Genre Classification

This project focuses on classifying music tracks into different genres using machine learning techniques on the Free Music Archive (FMA) dataset.

## Overview
The project explores both supervised and unsupervised learning approaches for music genre analysis using extracted audio features.

Supervised models:
- Random Forest
- XGBoost
- CatBoost
- Feedforward Neural Network (FNN)

Unsupervised models:
- K-Means Clustering
- HDBSCAN
- Multi-stage Clustering (HDBSCAN + K-Means)

## Dataset
- Free Music Archive (FMA)
- 106,574 music tracks
- 518 extracted audio features per track
- 16 music genres

## My Contributions
- Data preprocessing
- Exploratory Data Analysis (EDA)
- XGBoost model implementation and evaluation

## Results
- Best supervised model: XGBoost
- Best clustering model: HDBSCAN

XGBoost achieved the highest performance with:
- Accuracy: 67.5%
- Macro F1-score: 64.7%

HDBSCAN achieved the best clustering quality with:
- Silhouette Score: 0.509

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- TensorFlow / Keras
- UMAP
- HDBSCAN
- Matplotlib
- Google Colab

## Files
- Project report
- Code notebooks
- The link of the dataset

## Team Members
- **Shumukh Eid Alotaibi** — Preprocessing, EDA, XGBoost Model
- Abeer Anwar Alansari — UMAP, HDBSCAN
- Bashayer Abdulaziz Alharbi — Preprocessing, FNN Model
- Hatoon Mohammed Ghabben — Preprocessing, UMAP, K-Means, Multi-stage Clustering
- Layal Mohammed Alhazmi — Preprocessing, EDA, Random Forest, CatBoost
