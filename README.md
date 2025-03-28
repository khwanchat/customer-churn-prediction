# 🧠 Customer Churn Prediction

This project uses machine learning models to predict whether a customer will churn from a bank, based on behavior and profile data.  
We explore multiple approaches including **Logistic Regression, Random Forest, CatBoost**, and **Explainable Boosting Machine (EBM)**.

---

## 📂 Project Structure

- `01_Baseline_Model.ipynb`: Simple benchmark using basic rules
- `02_Logistic_Regression.ipynb`: Classic interpretable model with feature engineering
- `03_Explainable_Boosting_Machine.ipynb`: Interpretable boosting model using Microsoft’s EBM
- `04_Random_Forest.ipynb`: Ensemble approach for performance benchmarking
- `05_CatBoost.ipynb`: Advanced gradient boosting that handles categoricals automatically

---

## 📊 Dataset

- Source: [Kaggle - Churn Modelling Dataset](https://www.kaggle.com/datasets/shubh0799/churn-modelling)
- 10,000 customer records from a fictional bank
- Features include age, credit score, geography, activity, balance, and more

---

## 🧠 Key Takeaways

- Tree-based models outperformed linear models in overall accuracy and ROC-AUC
- CatBoost provided strong performance with minimal feature tuning
- EBM offered a nice balance between interpretability and predictive power

---

## 🤝 Contributors

This was a group project completed as part of the Foundation of Business Analytics course.

**Team Members:**
- Khwanchat Phutphithak 
- Kuan Sheng Chen
- Pan Minwen
- Shota Sanada

---

## 🛠️ Tech Stack

- Python
- pandas, scikit-learn, catboost, interpret
- Jupyter Notebooks
- Matplotlib / Seaborn for visuals

---

## ✨ License

For academic and portfolio use only. Dataset is publicly available on Kaggle.

---

📌 Created as part of NUS MSBA coursework – 2025
