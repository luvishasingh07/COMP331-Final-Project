# COMP331-Final-Project
Final project for COMP 331 – Data Mining Quality &amp; Bias Analysis using the Adult Income dataset.

This repository contains the analysis notebook, figures, and results for my COMP331 final project on data quality issues in the UCI Adult Income dataset.

The Adult Income dataset, from the UCI Machine Learning Repository, consists of roughly 48,000 census records with demographic attributes such as age, gender, race, education, occupation, and a target label that indicates whether an individual earns more than $50,000 annually. While very commonly used in teaching and benchmarking machine learning models, this dataset is equally known for a number of data quality challenges that may impact both model performance and fairness. In particular, high-quality training data is crucial here, since demographic features are strongly correlated with income, and thus issues such as missing values or sampling bias may readily propagate to discriminatory predictions. In the following, I will concentrate on four data quality dimensions that are central to the data mining workflow: completeness, sampling bias, feature quality, and fairness. Together, these capture how well the dataset supports reliable and ethical predictive modeling.

## Contents
- `notebooks/analysis.ipynb`
- `figures/`
- `results/`
- `data/`
- `scripts/`
  
## Google Colab Notebook
Link to the notebook: https://colab.research.google.com/drive/1qAA8LcwGiTmPOKB5VQ_1KZUOatkWzSC6
