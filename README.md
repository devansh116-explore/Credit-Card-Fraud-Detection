🛡️ Credit Card Fraud Detection using Machine Learning


📌 Overview
This project aims to detect fraudulent credit card transactions using supervised machine learning techniques. Credit card fraud is a growing concern for financial institutions, and early detection can save millions of dollars and improve customer trust.
The dataset is highly imbalanced, making the task more complex and interesting. Various models were evaluated to find the most accurate and reliable approach to detect fraud.

📊 Dataset
Source: Kaggle Credit Card Fraud Detection
Details:
284,807 transactions
492 fraud cases (~0.172%)
Features: V1 to V28 (PCA-transformed), Time, Amount, Class (target: 0 = normal, 1 = fraud)

🧠 Machine Learning Pipeline
1. Data Preprocessing
Normalization of Amount
Dropped Time feature
Train-test split (stratified)
2. Exploratory Data Analysis
Class imbalance visualization
Feature distribution comparison for fraud vs non-fraud
3. Handling Imbalance
Used SMOTE (Synthetic Minority Oversampling Technique)
4. Model Training
Logistic Regression
Random Forest
XGBoost
K-Nearest Neighbors (KNN)
Decision Tree
5. Model Evaluation
Confusion Matrix
Precision, Recall, F1-Score
ROC Curve (optional)
6. Feature Importance
Visualized for tree-based models (e.g., XGBoost)

✅ Results
Model	Precision	Recall	F1-Score
Logistic Regression	0.92	0.89	0.90
Random Forest	0.96	0.94	0.95
XGBoost	0.97	0.95	0.96
Note: Metrics are illustrative. Check the notebook for actual scores.

📦 Libraries & Tools Used
Python 3.x
pandas, numpy
matplotlib, seaborn
scikit-learn
imbalanced-learn (SMOTE)
xgboost

💡 Future Improvements
Integrate real-time prediction API using Flask or FastAPI
Add SHAP/LIME for better explainability
Perform hyperparameter tuning with GridSearchCV
Deploy on cloud (e.g., AWS or Heroku)

📁 Project Structure
Credit_Card_Fraud_Detection/
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
└──  dataset

🧠 Author
Tanisha Gupta
Final-year B.Tech in Computer Science (AI Specialization)
LinkedIn (www.linkedin.com/in/tanisha-gupta-1030a1282)

