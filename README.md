📊 Customer Churn Prediction

A Data Science project that predicts whether a customer will churn (discontinue service) based on a real-world telecom dataset. This predictive model helps subscription-based businesses retain valuable customers.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

📌 Problem Statement

Customer churn leads to significant revenue loss. By predicting churn, companies can take preventive actions and improve customer retention.

---

🧠 Model Overview

- 📦 Machine Learning Algorithm: Random Forest Classifier
- 📈 Metrics: Accuracy, Precision, Recall, F1-score
- 🔍 Feature Engineering: Encoding, Missing value treatment, Scaling
- 🧪 Train-Test Split: 80/20

---

📂 Project Structure

📁 customer-churn-prediction
├── 📄 churn_prediction.py
├── 📄 requirements.txt
├── 📄 README.md
└── 📊 WA_Fn-UseC_-Telco-Customer-Churn.csv


---

📊 Dataset

- Name: Telco Customer Churn Dataset  
- Source: [Kaggle Dataset Link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 customer records  
- Attributes: Customer behavior, subscription details, demographics, etc.

---

🚀 How to Run

1️⃣ Clone the Repository
bash
git clone https://github.com/sreedinesh114/customer-churn-prediction.git
cd customer-churn-prediction
2️⃣ Install Dependencies
bash
pip install -r requirements.txt
3️⃣ Run the Script
bash
python churn_prediction.py

✅ Output Includes
✔️ Confusion Matrix
 [[922 111]
 [199 175]]

✔️ Classification Report
precision    recall  f1-score   support
 0       0.82      0.89      0.86      1033
 1       0.61      0.47      0.53       374
✔️ Accuracy Score
    accuracy                           0.78      1407
   macro avg       0.72      0.68      0.69      1407
weighted avg       0.77      0.78      0.77      1407

✔️ Feature Importance Plot


---

🚀 Next Step (Optional)

Would you like me to:
- Add this `README.md` directly to your project as a file?
- Help generate a **Streamlit UI** for this?
- Or help you make a GitHub portfolio to showcase your projects?

Let me know — you're building an impressive Data Science profile!
