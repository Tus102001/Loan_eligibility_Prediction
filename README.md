# 🏦 Loan Eligibility Prediction App

Welcome to the Loan Eligibility Prediction App — a Streamlit-powered web application developed by **Tushar Chaudhary**. This app uses a trained machine learning model to determine whether a loan application is likely to be approved based on user-provided financial and demographic details.

---

## 🚀 Demo

👉 **Live App:** [Click here to open]([https://share.streamlit.io/your-app-url](https://loaneligibilityprediction-bh9h9h8nb3bvawhdxovezq.streamlit.app/)

---

## 🎯 Features

- ✅ Predicts loan approval with trained ML model
- 📊 Takes applicant income, loan amount, credit history, education, etc.
- 🔐 Uses a `scaler.pkl` to normalize inputs for accurate predictions
- 💬 Friendly UI with Streamlit + custom emojis
- 🧾 Logs predictions and errors into a local file (`loan_app.log`)
- 💥 Error handling to avoid crashes

---

## 🧠 Technologies Used

- Python
- Streamlit
- scikit-learn
- NumPy
- Pickle (for model persistence)

---

## 📁 Project Structure

Loan_Eligibility_App/
├── app.py # Streamlit app
├── model.pkl # Trained ML model (e.g., Logistic Regression)
├── scaler.pkl # Fitted scaler (e.g., StandardScaler or MinMaxScaler)
├── loan_app.log # Log file for predictions and errors
├── requirements.txt # Python dependencies
└── README.md # This documentation

yaml
Copy
Edit


---

## 📥 Installation

To run the app locally:

1. **Clone the repository**

```bash
git clone https://github.com/TusharChaudhary/Loan_Eligibility_App.git
cd Loan_Eligibility_App

Install the required libraries

bash
Copy
Edit
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py

