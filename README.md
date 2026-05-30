# Census Income Classification

## Project Overview
This project uses supervised machine learning models to predict whether an individual's annual income exceeds $50K based on demographic and employment-related census attributes.

## Why Does Income Prediction Matter?

Income prediction is an important application of machine learning because it helps organizations, policymakers, and researchers better understand the socioeconomic factors that influence earning potential. By identifying patterns in demographic, educational, and employment-related data, predictive models can support more informed decision-making across various sectors.

Accurate income classification has several practical applications, including:

* **Workforce Analytics:** Understanding income trends across different occupations, education levels, and demographic groups.
* **Financial Services:** Supporting credit risk assessment, loan eligibility analysis, and personalized financial product recommendations.
* **Economic Research:** Analyzing socioeconomic disparities and identifying factors associated with higher or lower income levels.
* **Policy Development:** Assisting governments and institutions in designing targeted programs aimed at reducing income inequality and improving access to opportunities.
* **Business Intelligence:** Helping organizations segment customers and develop data-driven strategies based on purchasing power and income characteristics.

In this project, machine learning techniques are used to predict whether an individual's annual income exceeds $50,000 based on census data. By comparing multiple classification algorithms, the project demonstrates how data-driven approaches can be applied to solve real-world predictive analytics problems while highlighting the strengths and limitations of different machine learning models.


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
Best Model: XGBoost

Accuracy: 87%

ROC-AUC: 0.92

## ROC Curve Comparison
![ROC Curve](https://github.com/Philipkarl25/census-income-classification/blob/main/roc_curve.png)

## Future Improvements
- Hyperparameter tuning
- SHAP explainability
- Deployment
- Cross-validation
