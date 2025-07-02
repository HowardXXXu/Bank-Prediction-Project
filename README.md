# Bank-Prediction-Project

- Engineered end-to-end data preprocessing pipeline: Managed 10K+ customer records by standardizing numerical features (credit score, balance), encoding categorical variables (geography, gender), and optimizing train-test splits (75:25 stratified sampling).

- Built and evaluated 3 classification models (Logistic Regression, KNN, Random Forest), selecting Random Forest as optimal via hyperparameter tuning (GridSearchCV), achieving 86% AUC and 86% accuracy on unseen data.

- Identified key drivers of churn (age, geography, inactive members) through feature importance analysis, enabling targeted retention strategies that reduced model false negatives by 22% (recall: 0.78).
