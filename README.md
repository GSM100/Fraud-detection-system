# Fraud-detection-system
End-to-end fraud detection system using machine learning


# Objective
The goal of this project is to detect fraudulent credit card transactions using machine learning techniques.

---

# Dataset
- Contains 284,807 transactions
- Fraud cases: 492 (~0.17%)
- Highly imbalanced dataset

---

# Exploratory Data Analysis (EDA)
- Checked class imbalance
- Visualized fraud vs normal transactions
- Analyzed transaction amount distribution
- Performed correlation analysis

# Key Insights:
- Fraud transactions are extremely rare
- Dataset is highly imbalanced
- Features are transformed using PCA
- Accuracy is not a reliable metric

---
# Data Preprocessing
- Scaled 'Amount' and 'Time' features
- Split data into training and testing sets
- Maintained class distribution using stratified sampling
  
# Model Building
- Logistic Regression (baseline)
- Random Forest (final model)
- Evaluated using recall, precision, F1-score, ROC-AUC

# Tools Used
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn
