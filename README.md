#Credit Risk Modeling
📌 Project Overview
Credit risk modeling is essential for financial institutions to evaluate the probability of a borrower defaulting on a loan. This project provides an interactive credit risk assessment system powered by machine learning. It evaluates borrowers' default risk, calculates credit scores, and assigns credit ratings. The system is built using Python and Streamlit, offering a user-friendly web-based interface.

🎯 Default Risk Prediction: Model Evaluation and Deployment
Objective
Develop a machine learning model to predict default risk with a focus on both accuracy and interpretability, suitable for real-world deployment.

📊 Key Features
Dataset: Imbalanced classification problem with approximately 10% default instances.

Feature Engineering: Based on domain knowledge and statistical relevance.

Resampling Methods:

Over-sampling using SMOTE

Under-sampling to balance class distribution

Models Evaluated:

Logistic Regression

Random Forest

XGBoost

✅ Selected Model
Final Model: XGBoost with Optuna hyperparameter tuning and under-sampling

Performance Metrics:

AUC: 0.98

Gini Coefficient: 0.97

KS Statistic: 86.87%

Interpretability Tools:

SHAP: Global feature importance

LIME: Local interpretability for individual predictions

🧪 Key Results
The model shows a high ability to classify defaults with strong precision and recall.

Decile analysis confirms effective risk separation.

AUC-ROC curve indicates near-perfect performance.

SHAP summary plots highlight top contributing features.

🚀 Deployment Readiness
Strengths:

High-performance metrics across evaluation criteria

Interpretability aligns with business and regulatory requirements

Mitigation Strategies:

Periodic retraining to address under-sampling risks

🧰 How to Use
Train the Model
Scripts are provided for data preprocessing, model training, and hyperparameter tuning.

Evaluate the Model
Includes tools for generating evaluation metrics, decile analysis, and interpretation plots.

Deploy the Model
Prebuilt pipeline and Streamlit app for real-time user interaction and integration into business systems.

💡 Why This Project Stands Out
Combines advanced machine learning techniques with interpretable results.

Solves a real-world business challenge with precision.

Designed for both research and production deployment.

🖥️ Running the Project: Credit Risk Modeling
Features
Interactive Credit Risk Assessment:

Input borrower and loan details

Receive real-time prediction with credit score and rating

Advanced Machine Learning:

Fine-tuned XGBoost model ensures accurate results

Scalable Architecture:

Modular design with reusable utility functions
