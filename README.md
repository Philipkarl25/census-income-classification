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

## Project Workflow

1. Data Loading and Inspection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Encoding and Scaling
5. Model Training
6. Model Evaluation and Comparison
7. Model Selection
8. Conclusion and Recommendations

## Repository Structure

├── census_income_classification.ipynb
├── roc_curve.png
├── README.md
└── requirements.txt

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook

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

## Key Findings

- XGBoost achieved the highest predictive performance with an Accuracy of 87% and ROC-AUC of 0.92.
- Ensemble methods (XGBoost and Random Forest) consistently outperformed individual learners.
- Education level, age, hours worked per week, and occupation showed strong predictive influence on income classification.
- The project demonstrates the effectiveness of boosting algorithms for structured tabular data.

## ROC Curve Comparison
![ROC Curve](https://github.com/Philipkarl25/census-income-classification/blob/main/roc_curve.png)

## Conclusion

This project successfully developed and compared seven machine learning models for income classification using the Adult Census dataset. Among all models evaluated, XGBoost achieved the best overall performance with an Accuracy of 87% and ROC-AUC of 0.92.

The results demonstrate that ensemble learning techniques are highly effective for structured tabular datasets and can provide valuable insights into socioeconomic income prediction problems.

Future work will focus on hyperparameter optimization, model explainability using SHAP, deployment through Streamlit, and production-ready machine learning pipelines.

## Future Improvements
- Hyperparameter tuning
- SHAP explainability
- Deployment
- Cross-validation

