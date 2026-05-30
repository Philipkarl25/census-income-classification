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

## Dataset
**Source:** UCI Machine Learning Repository — Adult Census Income Dataset  
**Original Source:** 1994 U.S. Census Bureau data, extracted by Barry Becker  
**Size:** 48,842 records × 15 features  
**Task Type:** Supervised Binary Classification  
**Class Distribution:** ~76% earn ≤$50K | ~24% earn >$50K (imbalanced)

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

## Results
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
