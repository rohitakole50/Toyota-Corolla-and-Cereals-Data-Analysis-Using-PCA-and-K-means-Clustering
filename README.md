# Toyota-Corolla-and-Cereals-Data-Analysis-Using-PCA-and-K-means-Clustering

## Overview:

This project involves a comprehensive analysis of two datasets: the Toyota Corolla dataset and a cereals dataset. Principal Component Analysis (PCA) is applied to the Toyota Corolla dataset to reduce dimensionality and understand the underlying patterns in the data. K-means clustering is used on the cereals dataset to identify clusters of healthy and unhealthy cereals. This project is part of the coursework for the Predictive Modeling class at the University of Connecticut.

## Objectives:

* To apply Principal Component Analysis (PCA) on the Toyota Corolla dataset to identify key components and reduce dimensionality.
* To determine the correlation between the saved principal components.
* To perform K-means clustering on a cereals dataset to identify clusters of healthy and unhealthy cereals.

## Key Components:

### 1. Principal Component Analysis (PCA) on Toyota Corolla Dataset:

* **Objective:** To reduce the dimensionality of the Toyota Corolla dataset while retaining as much variability as possible.
* **Analysis:**
  * Conducted PCA and identified that the first two principal components (PC1 and PC2) maintain about 48.92% variability.
  * PC1 is primarily influenced by Price (54.92%) and Weight (43.48%), with Age_08_04 contributing the least (-50.78%).
  * PC2 is significantly influenced by Quarterly Tax (57.53%) and KM (46.02), with HP providing the least information (-36.74%).
  * To achieve ideal variability, at least five components are required to retain 80.12% variability.

### 2. Correlation Analysis of Principal Components:

* **Objective:** To determine the correlation between the two saved principal components.
* **Analysis:**
  * The correlation matrix shows that PC1 and PC2 are perfectly uncorrelated (orthogonal) to each other, with a correlation of 1.00 for P1 to P1 and P2 to P2, and 0.00 for P1 to P2 and P2 to P1.
  * This indicates that both components capture different aspects of the data.

### 3. K-means Clustering on Cereals Dataset:

* **Objective:** To identify the healthiest and least healthy clusters of cereals for a public elementary school's cafeteria.
* **Analysis:**
  * **Healthiest Cluster:** Cluster 2 has the lowest calories, highest protein, no fat, lowest sodium, highest fiber, no sugar, and the highest overall rating (93.7049).
  * **Least Healthy Cluster:** Cluster 4 has the highest calories (116.667), highest sodium (208.333), highest carbs (18.167), high sugar (6.333), and the lowest overall rating (38.0984).

## Tools and Technologies:

* SAS JMP software for data analysis, PCA, and clustering.
* Microsoft Word for documenting the analysis and findings.

## Conclusion:

The Toyota Corolla and Cereals Data Analysis project demonstrates the application of Principal Component Analysis to reduce dimensionality and identify key components influencing the Toyota Corolla dataset. Additionally, the project showcases the use of K-means clustering to identify healthy and unhealthy clusters in a cereals dataset. Through various analyses and visualizations, the project provides valuable insights into the underlying patterns and relationships in both datasets.

## References:

* Pankaj Prakash, OPIM5604 Predictive Modeling, University of Connecticut.
* Toyota Corolla Dataset.
* Cereals Dataset.
