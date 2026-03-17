# credit-card-fraud-detection

A machine learning project to detect fraudulent credit card transactions using real-world data.

---

## 📌 Overview
- Preprocessed 100K+ credit card transactions
- Features include: card type, amount, country, age, transaction type, etc.
- Addressed class imbalance using **SMOTE**
- Applied **PCA** for dimensionality reduction
- Trained and evaluated:
  - ✅ **XGBoost**
  - 🌲 **Random Forest**

---

## 🚀 Model Performance

| Model         | Precision | Recall | F1 Score | Accuracy | AUC   |
|---------------|-----------|--------|----------|----------|--------|
| **XGBoost**       | 0.77      | 0.80   | 0.78     | 96.78%   | 0.967 |
| **Random Forest** | 0.71      | 0.84   | 0.77     | 96.37%   | 0.961 |

---

## 🧠 Tools & Techniques
- 🧹 Data Cleaning & One-Hot Encoding  
- 📊 Feature Scaling (`StandardScaler`)  
- ⚖️ SMOTE for class balancing  
- 🔍 PCA (95% variance retained)  
- ✅ Classification with **XGBoost** and **RandomForest**  
- 📈 Evaluation using Accuracy, Precision, Recall, F1, AUC  

---

## 💾 Output
Trained models are saved as:
- `xgboost_fraud_model.joblib`
- `random_forest_fraud_model.joblib`

---

## 📣 Conclusion
Both models performed well, with **XGBoost** showing slightly better accuracy and precision. The project demonstrates a full ML pipeline from preprocessing to model deployment

---


##  Add 🔮 Future Improvements
- Deploy model using Flask / FastAPI
- Integrate real-time fraud detection API
- Use Deep Learning models (LSTM for sequential patterns)
- Hyperparameter tuning using Optuna
- Add Explainability (SHAP / LIME)

---


