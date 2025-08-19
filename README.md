# Credit Card Default Prediction
## Project Overview

This project focuses on predicting credit card default risk using a dataset of 30,000+ client records from the UCI Machine Learning Repository. 
The goal was to analyze client behavior, address class imbalance, and build robust classification models that can help financial institutions identify at-risk clients early.

## Objectives

Perform exploratory data analysis (EDA) to uncover behavioral and financial patterns.

Build and evaluate multiple classification models to predict defaults.

Address class imbalance to improve real-world predictive performance.

Communicate results effectively through visualizations and model comparison.

##  Dataset

Source: Default of Credit Card Clients Dataset, UCI ML Repository

Records: 30,000+

Features: Demographics, financial status, repayment history, and bill/payment data.

Target Variable: default.payment.next.month (1 = default, 0 = non-default)

##  Methodology

Data Preprocessing

Handled missing values and outliers.

Scaled features using StandardScaler.

Applied Stratified K-Fold Cross Validation for consistent evaluation.

Exploratory Data Analysis (EDA)

Correlation heatmaps for feature relationships.

Boxplots & distribution plots for variable insights.

Outlier detection and removal.

Modeling

Logistic Regression

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Class Imbalance Handling

Applied SMOTE (Synthetic Minority Oversampling Technique).

Improved recall by 42.9% in Logistic Regression.

Evaluation Metrics

Accuracy

Precision, Recall, F1-score

Confusion Matrices

Comparative performance plots


##  Key Results

Random Forest achieved the best performance:

Accuracy: 79.6%

F1-Score: 49.6%

SMOTE significantly boosted recall, making models more effective in detecting defaulters.


##  Tools & Libraries

Python

pandas, numpy

matplotlib, seaborn

scikit-learn

imbalanced-learn

##  Visualizations

Correlation heatmaps

Confusion matrices

Bar charts & comparative model plots



##  Future Improvements

Hyperparameter tuning for better model optimization.

Testing advanced ensemble methods (XGBoost, LightGBM, CatBoost).

Deployment as a web app for real-world use.


## Files in this Repository

Jupyter Notebook containing full workflow including data preprocessing, EDA, feature engineering, model training, and evaluation.


## Notes

All analysis was performed in Google Colab using Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, and imblearn.

Due to dataset size, raw data is not uploaded in this repository. Please download it directly from UCI if you wish to reproduce results.


## Contact
For questions or feedback, feel free to reach out via LinkedIn: [Yashaswi Bastakoti (https://www.linkedin.com/in/yashaswib/)]
