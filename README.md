## TabNet-Driven Predictive Modeling of Typhoid Fever Using Clinical Biomarkers in a Bangladeshi Cohort 🇧🇩

## Description

This repository contains a machine learning pipeline designed to predict typhoid fever diagnosis based on clinical biomarkers collected in Bangladesh. The project leverages TabNet, a deep learning model tailored for tabular data, and Bayesian optimization for hyperparameter tuning. Key features include handling class imbalance using weighted loss, rigorous model evaluation across multiple random seeds, and feature importance with multicollinearity analysis.

---

## Overview

The pipeline preprocesses clinical and demographic data, extracts meaningful features, performs feature importance and variance inflation factor (VIF) analyses, and develops robust TabNet-based classifiers. The models were evaluated repeatedly over several random seeds to ensure reproducibility, with average ROC curves and AUC statistics reported. This approach promotes interpretable, parsimonious, and high-performance diagnostic tools suitable for resource-limited healthcare environments.

---

## File Structure

- `typhoid-predict-tabnet-bangladesh-cleaned.ipynb`: Jupyter notebook containing the complete analysis pipeline, including data preprocessing, feature engineering, model training with Bayesian optimization, evaluation, and visualization.

---

## Graphical Summary

![Average ROC Curve](average_roc_curve_th_titer.png)

*Figure*: ROC curve for the TabNet model trained using only the `TH_titer` feature. The model achieved an average AUC of 1.000 ± 0.000 across multiple seeds, demonstrating that feature dimensionality was significantly reduced without compromising predictive accuracy.

---

## License

This project is licensed under the MIT License. 

---

## Questions?

For questions or clarifications (or maybe collaboration opportunities!), please open an issue or contact jprmaulion[at]gmail[dot]com.
