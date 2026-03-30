# ML Neural Network & Clustering Explainability Dashboard

This repository contains machine learning projects focused on educational data science, specifically student performance analysis and graduate admission predictions. It explores advanced clustering techniques for mixed-type data and explainable AI (XAI) models.

##Projects Overview

### 1. Student Performance Clustering & Dimensionality Reduction
This project analyzes student academic data to identify patterns and groupings using unsupervised learning.
- [cite_start]**Dataset:** `10_Student_Performance.xlsx` 
- **Core Methodology:**
    - [cite_start]**k-Prototypes Clustering:** Used specifically for mixed data (numeric and categorical features).
    - [cite_start]**Optimal Cluster Selection:** Determined using the **Elbow Method**, identifying 3 clusters as the optimal point where cost reduction diminishes.
    - [cite_start]**Dimensionality Reduction:** Implementation of **PCA/MCA/FAMD** and **t-SNE** to visualize high-dimensional student data in 2D and 3D spaces[cite: 1].
    - [cite_start]**Validation:** Comparative analysis of clustering results before and after dimensionality reduction to ensure at least 85% variance is preserved[cite: 1].

### 2. Graduate Admission & Success Prediction
*(Integrated from previous project tasks)*
- [cite_start]**Models:** Deep Neural Networks (Keras/TensorFlow) testing various architectures (ReLU, Tanh, ELU).
- [cite_start]**Explainability:** Implementation of **LIME** (Local Interpretable Model-agnostic Explanations) to provide transparency into how individual features like CGPA or GRE scores affect predictions.

## Tech Stack
- [cite_start]**Languages:** Python 3.12 
- [cite_start]**Clustering:** `kmodes` (k-Prototypes) 
- [cite_start]**Deep Learning:** TensorFlow, Keras 
- [cite_start]**Explainable AI:** LIME 
- [cite_start]**Data Science:** Scikit-Learn, Pandas, NumPy, Plotly (for 3D visualizations) [cite: 1, 2]

