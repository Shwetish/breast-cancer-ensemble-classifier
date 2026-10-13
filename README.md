# breast-cancer-ensemble-classifier
Medical diagnostic classification system applying advanced ensemble algorithms (Bagging, Boosting, Stacking, Voting) to distinguish between benign and malignant tumors with minimal false negatives.

# Breast Cancer Diagnostic Classification Suite

## 1. Business Problem
* **Objective:** Accurately classify tumor samples as benign or malignant to assist doctors in clinical decision-making.
* **Constraints:** Minimizing false negatives and false positives is critical due to the life-threatening implications of misdiagnosis in medical oncology.

## 2. Data Dictionary & Feature Engineering
* Comprehensive feature mapping of cell nuclei characteristics (radius, texture, perimeter, area, smoothness, etc.).
* Outlier treatment, data cleaning, and feature scaling.

## 3. Exploratory Data Analysis & Modeling
* **EDA:** Summary statistics, distribution plots, and correlation heatmaps.
* **Ensemble Models:** 
  * Bagging & Boosting (AdaBoost, FastAdaBoost, XGBoost)
  * Stacking & Voting classifiers
* **Hyperparameter Tuning:** GridSearchCV for optimal threshold and parameter selection evaluated via confusion matrices.

## 4. Business Impact
* Minimizes medical diagnostic errors, enhances patient safety, and provides reliable clinical insights to support pathologists in critical evaluations.
