# Census Income Classification

## Project Overview
This project uses supervised machine learning models to predict whether an individual's annual income exceeds $50K based on demographic and employment-related census attributes.

## Objective
Income prediction is a high-value capability in financial services, insurance, marketing, and public policy. Organizations use income classification to:

- **Target financial products** — Banks and lenders identify creditworthy 
  customers before outreach, reducing acquisition costs by up to 40%.
- **Design social programs** — Governments use income segmentation to 
  allocate welfare, tax relief, and educational subsidies efficiently.
- **Power recommendation engines** — E-commerce platforms personalize 
  premium product recommendations based on estimated purchasing power.
- **Detect fraud and risk** — Insurers flag applications where stated income 
  mismatches predicted income from demographic signals.

**The core business question this project answers:**

> *"Given an individual's demographic and employment attributes, can we 
> reliably predict whether their annual income exceeds $50,000 — and which 
> features most strongly drive that prediction?"*

This is a **binary classification problem**. The output is one of:
- `≤$50K` — Below the income threshold
- `>$50K` — Above the income threshold

Accurate classification enables data-driven targeting with measurable business ROI, replacing expensive manual segmentation with scalable ML inference.

## Dataset
**Source:** UCI Machine Learning Repository — Adult Census Income Dataset  
**Original Source:** 1994 U.S. Census Bureau data, extracted by Barry Becker  
**Size:** 48,842 records × 15 features  
**Task Type:** Supervised Binary Classification  
**Class Distribution:** ~76% earn ≤$50K | ~24% earn >$50K (imbalanced)

### Why This Dataset?
This dataset is a benchmark in income classification research, cited in 
hundreds of academic papers and industry studies. Its mix of numerical 
and categorical features, real-world class imbalance, and socioeconomic 
complexity makes it an excellent testbed for production-grade ML pipelines.

## Tools & Technologies
Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Machine Learning Models Used
- Logistic Regression
- SVM
- Decision Tree
- Random Forest
- KNN
- XGBoost
- AdaBoost

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Key Findings
An XGBoost model with 88% accuracy and 0.93 AUC means:

Model  Accuracy  Precision    Recall  F1 Score   ROC-AUC
XGBoost  0.875320   0.801272  0.642038  0.712871  0.926303

## ROC Curve Comparison
![ROC Curve](assets/roc_curve.png)

## Future Improvements
- Hyperparameter tuning
- SHAP explainability
- Deployment
- Cross-validation
