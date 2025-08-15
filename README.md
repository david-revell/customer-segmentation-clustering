# Customer Segmentation with Clustering

This project applies clustering techniques to segment a global e-commerce customer base. Using features like frequency, recency, and customer lifetime value (CLV), it identifies distinct customer profiles to support targeted marketing and strategic decision-making.

---

## Project Overview

The goal is to group customers into meaningful clusters based on behavioural and demographic features. Multiple clustering methods are compared and evaluated visually and numerically to determine the most interpretable segmentation.

**Techniques used:**
- K-Means Clustering (with Elbow and Silhouette methods)
- Hierarchical Agglomerative Clustering
- Dimensionality reduction via PCA and t-SNE

*Full PDF report included in the repo.*

---

## Key Steps

1. Engineer features: Frequency, Recency, CLV, Age, AUC
2. Scale features and apply clustering algorithms
3. Use Elbow method and Silhouette scores to tune cluster count
4. Visualise clusters with PCA and t-SNE
5. Profile customer segments for strategic insight

---

## Status

All modelling and analysis are contained in a single Jupyter Notebook.  
Visual outputs are saved, and the notebook runs end-to-end with no external dependencies.
