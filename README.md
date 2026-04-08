
# 💳 Fraud Detection Web App

A Machine Learning-based web application built using Streamlit that predicts whether a financial transaction is fraudulent or not.

---

## 🚀 Features

* Predicts fraud transactions using trained ML model
* Simple and interactive UI using Streamlit
* Real-time prediction based on user input
* Supports multiple transaction types

---

## 🧠 Machine Learning Model

The model is trained using transaction data and saved as a pipeline (`fraud_detection_pipeline.pkl`).
It considers features like:

* Transaction Type
* Amount
* Sender Balance (Old & New)
* Receiver Balance (Old & New)

---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Streamlit
* Joblib

---

## 📂 Project Files

* `fraud_detection.py` → Streamlit App
* `fraud_detection_pipeline.pkl` → Trained ML Model
* `analysis_model.ipynb` → Model training notebook

---

## ▶️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-username/fraud-detection-app.git
cd fraud-detection-app
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run fraud_detection.py
```

---

## 📸 App Preview

The app allows users to input transaction details and predicts whether the transaction is fraudulent.

---

## ⚠️ Output

* **1 → Fraudulent Transaction**
* **0 → Legitimate Transaction**

---

## 📌 Future Improvements

* Add model accuracy visualization
* Deploy on Streamlit Cloud / Render
* Improve UI design
* Add transaction history tracking

---

## 👩‍💻 Author

**Sakshi Vinod Kumbhare**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
