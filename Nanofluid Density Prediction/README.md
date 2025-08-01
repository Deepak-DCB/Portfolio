# Hybrid Nanofluid Density Analysis

**Author:** Deepak Binkam  
**Course:** Data Mining (COSC 757), Towson University

---

## Overview

This folder contains two complementary projects focused on the analysis and prediction of hybrid nanofluid density using both supervised and unsupervised machine learning techniques. Hybrid nanofluids, with enhanced thermal properties, are important for advancing heat exchanger, automotive, and electronics cooling technologies.

- **Regression Analysis:** Predicts nanofluid density using linear and ensemble regression models.
- **Clustering Analysis:** Discovers natural groupings in nanofluid data, revealing patterns related to temperature, composition, and concentration.

Both projects use the same experimental dataset of 436 hybrid nanofluid samples (sourced from Kaggle and peer-reviewed literature).

---

## Contents

- `NanoparticleDensityPredRegression.ipynb` – Jupyter/Colab notebook for regression models
- `NanoparticleDensityPredClustering.ipynb` – Jupyter/Colab notebook for clustering analysis
- `HybridNanofluidDensityRegression.pdf` – Formal report (regression)
- `HybridNanofluidDensityClustering.pdf` – Formal report (clustering)
- (Add any data files or external links as needed)

---

## Project 1: Density Prediction Using Regression

- **Goal:** Accurately predict hybrid nanofluid density using machine learning (Linear Regression, Decision Tree, Random Forest).
- **Highlights:**
    - Data cleaning, EDA, and feature engineering (polynomial features, robust scaling)
    - Achieved R² > 0.99 on test set
    - Discussion of linear vs. non-linear models and overfitting
- **Notebook:** `NanoparticleDensityPredRegression.ipynb`
- **Report:** `HybridNanofluidDensityRegression.pdf`

---

## Project 2: Density Analysis Using Clustering

- **Goal:** Identify natural clusters among nanofluid samples based on physical and compositional features.
- **Highlights:**
    - K-Means, Agglomerative, and DBSCAN clustering
    - Feature engineering and PCA-based visualization
    - Interpreted clusters for insights on temperature/concentration effects
- **Notebook:** `NanoparticleDensityPredClustering.ipynb`
- **Report:** `HybridNanofluidDensityClustering.pdf`

---

## Getting Started

1. Open the desired notebook (`.ipynb`) in Jupyter, Colab, or VS Code.
2. Follow the cell-by-cell workflow; each is fully commented for reproducibility.
3. Data file: If required, download the [Kaggle nanofluid dataset](https://www.kaggle.com/datasets/...) (insert actual link) and place in the same folder.

---

## Author Contribution

All code, analysis, and reports were prepared by Deepak Binkam for academic and portfolio purposes.

---

## License

For educational use only. Please contact for collaboration or commercial inquiries.

---

