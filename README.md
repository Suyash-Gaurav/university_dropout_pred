# university_dropout_pred



# Student Academic Success Analysis

## Introduction

This analysis aims to identify the key factors influencing student academic success, with a focus on predicting student status (dropout, enrolled, or graduated) using various features related to academic performance, demographics, and financial conditions.

## Data Preprocessing

- Correlation analysis (Pearson and Spearman) to identify relevant features
- Removed features with weak correlation to the target variable
- Created interaction and aggregated features to capture combined effects

## Exploratory Data Analysis

### Academic Performance

- Interaction between first and second semester grades shows a clear upward trend from dropouts to graduates, indicating its strong influence on student status.[1]
- Total approved curricular units also exhibits an increasing trend from dropouts to graduates, highlighting its predictive power.[1]

### Financial Status

- Students with debt have a higher dropout rate compared to those without debt, suggesting financial obligations hinder educational continuity.[1]
- Scholarship recipients have a higher graduation rate, indicating financial support aids in completing education.[1]
- Students with outstanding tuition fees are more likely to drop out, making this a potent predictor of discontinuation.[1]

### Age and Gender

- Age distribution analysis and visualizations (to be included based on the provided code)
- Insights on the interplay of age and gender with student status (to be derived from the provided code)

## Machine Learning Models

Various machine learning models were configured and evaluated, including:

- Gradient Boosting
- Random Forest
- Logistic Regression
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)

The models were trained using pipelines with preprocessing steps like scaling, SMOTE for imbalanced data handling, and PCA for dimensionality reduction. Hyperparameter tuning and learning curve analysis were performed to optimize model performance.



## Conclusion

This analysis highlights the significant impact of academic performance, financial status, and demographic factors on student academic success. The findings can inform targeted interventions and support systems to improve student retention and graduation rates.



Note: This structure provides a high-level overview of the analysis, with placeholders for including specific visualizations, model evaluation results, and additional insights based on the provided code and analysis.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/15728973/c5b2b42e-db94-4d9c-8fe0-cefee0da7f62/paste.txt
