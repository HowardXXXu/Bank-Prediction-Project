# Customer Churn Prediction | Banking Analytics
Machine Learning Project

📌 Objective
Developed a predictive model to identify high-risk churning customers for a financial institution, enabling proactive retention strategies and reducing revenue loss.

🔧 Technical Approach

Engineered end-to-end data preprocessing: Standardized numerical features, encoded categorical variables (OneHot/Ordinal Encoding), and split data via stratified sampling.

Trained/optimized 3 ML models (Logistic Regression, KNN, Random Forest) using GridSearchCV, achieving 86% AUC with tuned Random Forest.

Evaluated performance via confusion matrices, ROC curves, and feature importance analysis (key drivers: Age, Geography, Activity Status).

📊 Key Results

86% accuracy and 86% AUC on test data.

Identified France-based inactive female customers (45+ years) as 3.1× more likely to churn.

Actionable insights delivered to reduce false negatives by 22% (recall: 0.78).

Tools: Python (Pandas, Scikit-learn), Matplotlib/Seaborn, Google Colab
Dataset: 10,000+ bank customer records (Credit Score, Geography, Tenure, etc.)
