# NASA OSDR Gene Expression Analysis (Explainable AI)

## Overview

This repository contains a set of Jupyter notebooks developed while working with datasets from the NASA Open Science Data Repository (OSDR).

The work focuses on applying machine learning and explainable AI techniques to gene expression data derived from spaceflight and ground control experiments.

The primary goal is to understand:

* How gene expression differs between spaceflight and ground samples
* Which genes are most influential in classification and regression tasks
* How different models interpret feature importance

---

## Objectives

* Build classification models to distinguish biological conditions
* Apply regression models to predict physiological metrics (e.g., IOP)
* Interpret model behavior using explainable AI techniques
* Compare feature importance across different algorithms

---

## Methods & Models Used

* Logistic Regression
* Random Forest
* Linear Regression

---

## Explainability Techniques

* SHAP (Shapley Additive Explanations)
* Feature Importance (Impurity-based)
* Permutation Importance

---

## Key Insights

* Certain genes (e.g., Cryaa, Cryab, Crybb2) consistently appear across multiple models and importance methods
* Overlap between model importance suggests biologically relevant signals rather than model-specific noise
* SHAP analysis provides instance-level explanations, revealing how individual genes influence predictions

---

## Dataset Source

* NASA Open Science Data Repository (OSDR)
* Gene expression datasets from spaceflight experiments

---

## Repository Structure

* `*.ipynb` → Analysis notebooks
* Outputs include:

  * Model performance metrics
  * Feature importance rankings
  * SHAP visualizations

---

## Tools & Libraries

* Python
* pandas
* scikit-learn
* matplotlib / seaborn
* shap

---

## Notes

This work is part of a learning and applied exploration of explainable AI in biological data analysis, with a focus on space life sciences.

---

## Author

Olayinka Daniel Oyedola
