# Linear_and_Logistic_Regression
==================================================
REPORT - LOGISTIC REGRESSION

The logistic regression model demonstrated strong performance in predicting default risk, achieving 92.5% accuracy and a ROC-AUC of 0.971, confirming its ability to distinguish between defaulting and non-defaulting customers. The confusion matrix showed 85 true negatives and 10 true positives, with minimal false positives (3) and false negatives (2), indicating high reliability. The coefficients revealed that active loans (2.137) strongly correlate with default risk, while income (-1.215) and age (-0.423) have a negative impact—meaning higher-income and older clients are less likely to default. These findings can support credit risk assessment and help design better lending policies.
==================================================
REPORT - LINEAR REGRESSION

The model showed high accuracy (R²=0.9581) with average errors of 
R$37,114 (MAE) and R$46,808 (RMSE). Each additional m² increased 
prices by R$5,040, while extra bedrooms added R$18,934. Location 
revealed unexpected patterns: Downtown properties had lower valuation 
than Suburbs, while South Zone showed a slight increase of R$4,814.

==================================================
CONCLUSION

The comparative analysis of both machine learning models reveals key insights about 
predictive modeling. The logistic regression (Example 1) achieved moderate performance 
(92.5% accuracy, 0.80 F1-Score) in classification tasks, while the linear regression 
(Example 2) showed substantial prediction errors (MAE R$37k, RMSE R$46k) despite good 
R² (0.9581). These results demonstrate three critical lessons:
1. Model performance is highly dependent on data quality - synthetic data may lead to 
   misleading metrics
2. Algorithm selection should match problem complexity - simple models may require 
   additional feature engineering
3. Real-world applications demand rigorous validation - theoretical metrics don't always 
   reflect practical utility

The experiments underscore the importance of proper data preprocessing, model tuning, 
and comprehensive evaluation beyond basic accuracy metrics in machine learning projects.
