# Fraud Detection System

An end-to-end machine learning project to detect fraudulent transactions using advanced data preprocessing, imbalance handling, and classification models.

---

# Problem Statement

Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions are extremely rare. The goal is to build a model that can effectively detect fraud while minimizing false alarms.

---

# Project Workflow

- Data Loading
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Handling Imbalance using SMOTE
- Model Building
- Model Evaluation

---

# Handling Class Imbalance

- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Balanced minority (fraud) and majority classes
- Improved model learning capability

---

# Models Used

### Logistic Regression
- Used as a baseline model
- High recall but very low precision
- Generates many false positives

### Random Forest
- Ensemble learning model
- Balanced precision and recall
- Best overall performance

---

##  Model Performance (Random Forest)

- Precision: 0.85  
- Recall: 0.84  
- F1-score: 0.84  
- ROC-AUC: 0.97  

---

##  Key Insights

- SMOTE significantly improved model performance on minority class
- Random Forest outperformed Logistic Regression
- High recall ensures most fraud cases are detected
- Balanced precision reduces false alarms

---

# Conclusion

Random Forest is the optimal model for this problem as it provides a strong balance between fraud detection and minimizing false positives.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib / Seaborn

---

##  Resume Highlight

Built an end-to-end fraud detection system using SMOTE and Random Forest, achieving high recall and ROC-AUC of 0.97 on highly imbalanced transaction data.

---

## Future Improvements

- Hyperparameter tuning
- Real-time fraud detection system
- Deployment using Flask / Streamlit
