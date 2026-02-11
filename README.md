# Early Detection of Breast Cancer Through AI-Driven Analysis of Gene Expression Data

## Overview
This independent student research project explores the use of machine learning models for early detection and subtype classification of breast cancer using gene expression data.

Motivated by a family history of cancer, this project aims to investigate how artificial intelligence and genomic analysis can contribute to cancer research and early diagnostic strategies.

---

## Dataset

- Public microarray dataset: **GSE45827**
- Source: Gene Expression Omnibus (GEO)
- Subtypes included:
  - Luminal A
  - Luminal B
  - HER2-enriched
  - Basal-like
  - Normal tissue
  - Cell lines

---

## Methodology

1. Data preprocessing and normalization
2. Dimensionality reduction using Principal Component Analysis (PCA)
3. Supervised machine learning models:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
4. Model evaluation using classification accuracy and class-based metrics

---

## Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 97.3%    |
| SVM                 | 96.7%    |
| Random Forest       | 95.3%    |

Logistic Regression achieved the highest performance in multi-class classification.

---

## Biological Insights

Feature importance analysis identified biologically meaningful genes associated with breast cancer:

- ESR1 (Estrogen Receptor 1)
- CCNB2 (Cyclin B2)
- COL1A2 (Collagen Type I Alpha 2 Chain)

These findings align with known molecular mechanisms in breast cancer biology.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- GEO Microarray Dataset

---

## Project Type

Independent Student Research Project (Grade 10)

---

## Future Work

- Validation on larger independent datasets
- Integration with clinical data
- Exploration of deep learning models
## Visualizations

### PCA Projection of Breast Cancer Subtypes

![PCA Plot](figures/pca_plot.png)

### Top Genes Contributing to Classification

![Top Genes](figures/top_genes.png)
