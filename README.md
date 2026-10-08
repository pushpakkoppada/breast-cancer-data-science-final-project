# Breast Cancer Data Science Final Project

## Week 5 — Comprehensive Data Science Project: Reporting and Strategic Recommendations

This repository contains the final Week 5 data science project completed during the YUVA internship. It integrates the workflow developed during the earlier weeks into a single reproducible project covering data preparation, machine-learning development, evaluation, visualization, interpretation, and strategic recommendations.

### Project objectives
- Understand and prepare a structured classification dataset.
- Compare Logistic Regression and Random Forest.
- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
- Communicate results using professional visualizations.
- Analyze model errors and feature importance.
- Identify limitations and responsible-use considerations.
- Convert analytical findings into strategic recommendations.
- Define a practical future improvement roadmap.

### Dataset
The project uses the Wisconsin Diagnostic Breast Cancer dataset available through Scikit-learn. It contains 569 observations, 30 numerical predictor features, and two target classes.

### Models
1. Logistic Regression with feature standardization through a Scikit-learn Pipeline.
2. Random Forest as a non-linear ensemble comparison.

### Evaluation
The project uses:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix
- ROC curves
- Feature importance

### Key result
Logistic Regression achieved 98.25% test accuracy, 98.61% F1-score and 99.54% ROC-AUC on the held-out test set in the documented experiment.

These are benchmark results on this dataset and split. They do not establish clinical effectiveness or production readiness.

### Repository structure
```text
breast-cancer-data-science-final-project/
├── README.md
├── requirements.txt
├── src/
│   └── final_analysis.py
├── data/
│   └── breast_cancer_wisconsin_diagnostic.csv
├── results/
│   └── model_metrics.csv
├── visualizations/
│   ├── 01_class_distribution.png
│   ├── 02_model_performance_comparison.png
│   ├── 03_confusion_matrix.png
│   ├── 04_roc_curves.png
│   └── 05_feature_importance.png
└── report/
    └── Week5_Final_Report.docx
```

### Future improvements
- Stratified k-fold cross-validation
- Hyperparameter tuning
- Independent external validation
- Threshold and probability calibration
- SHAP/permutation-based interpretability
- Experiment tracking
- Model drift monitoring

### Responsible use
This is an educational data-science project. It is not a medical diagnostic system and should not be used for medical decision-making.
