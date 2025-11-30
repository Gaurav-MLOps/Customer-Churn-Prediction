# 📊 Customer Churn Prediction  
A full end-to-end machine learning project that predicts whether a customer is likely to churn based on their demographic and service usage data.

This project includes:
- Data cleaning & preprocessing  
- Feature engineering  
- Handling class imbalance using **SMOTE**  
- Training a **Random Forest** model inside an ML pipeline  
- A **Streamlit web app** for real-time churn prediction  
- Complete deployment using **Streamlit Community Cloud**

---

## 🚀 Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Imbalanced-Learn (SMOTE)**
- **Streamlit**
- **Joblib**

---

## 📁 Project Structure

customer-churn-prediction/
│── app.py # Streamlit app
│── model.pkl # Saved ML model
│── Telco-Customer-Churn.csv # Dataset
│── README.md # Project documentation
│── requirements.txt # Dependencies
│── Customer_Churn_Analysis.ipynb # Jupyter notebook (training)


---

## 🧠 Model Overview
- **Algorithm:** Random Forest Classifier  
- **Pipeline:**  
  - One-Hot Encoding for categorical features  
  - Standard Scaling for numerical features  
  - SMOTE oversampling to fix class imbalance  
- **Evaluation:**  
  - Accuracy  
  - Precision, Recall, F1  
  - ROC-AUC Score (≈ **0.81**)

---

## 🖥️ Streamlit App Details
The web app allows users to input customer information such as:
- Gender  
- Senior Citizen  
- Partner & Dependents  
- Monthly & Total Charges  
- Tenure  
- Contract type  
- Phone/Internet services  

The model instantly predicts:
- **Churn Risk (High / Low)**  
- **Probability Score**

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/Gaurav-MLOps/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
```

--- 

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

---

### 3. Run the Streamlit app
```bash
streamlit run app.py
```

---

### 📚 Dataset

Dataset used: Telco Customer Churn
Source: Kaggle
Includes ~7,000 customers with 20+ features.

---

### 🙌 Acknowledgements

Dataset by BlastChar on Kaggle.
Frameworks: Scikit-learn, Streamlit, Imbalanced-Learn.

---

### 👤 Author

Gaurav Singh
AI/ML & MLOps Learner | Building real-world ML projects