# 🏦 Loan Eligibility Prediction App

A Streamlit-based machine learning web application built by **Tushar Chaudhary** to predict whether a loan applicant is eligible based on financial and demographic information.

---

## 🚀 Live Demo

👉 **App Link**: [Click here to open](https://loaneligibilityprediction-bh9h9h8nb3bvawhdxovezq.streamlit.app/)

> _Replace with your actual Streamlit Cloud app URL_

---

## 🔁 Step 1: Clone the Repository

```bash
git clone https://github.com/TusharChaudhary/Loan_Eligibility_Prediction.git
cd Loan_Eligibility_Prediction
📦 Step 2: Install Dependencies
It is recommended to use a virtual environment.

bash
Copy
Edit
pip install -r requirements.txt
▶️ Step 3: Run the App
bash
Copy
Edit
streamlit run app.py
The app will launch in your default browser on http://localhost:8501

🧠 Model Info
Algorithm: Logistic Regression

Scaler: StandardScaler

Input Features:

Applicant Income

Co-applicant Income

Loan Amount

Loan Term

Credit History

Gender

Marital Status

Dependents

Education

Self Employment

Property Area

Output: Eligible (1) or Not Eligible (0)

📊 Dataset
credit.csv: contains anonymized applicant data used for training

Source: UCI Machine Learning Repository
or any other dataset used in model creation.

📁 Project Structure
bash
Copy
Edit
Loan_Eligibility_Prediction/
├── app.py              # Streamlit application script
├── model.pkl           # Trained Logistic Regression model
├── scaler.pkl          # Fitted StandardScaler
├── loan_app.log        # Application logs
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
🎯 Future Enhancements
🌐 Deploy on Streamlit Community Cloud or Heroku

📈 Improve model performance using Random Forest or XGBoost

🧾 Add interpretability (SHAP/LIME) for transparent predictions

📊 Connect to real-time credit scoring APIs

🔐 Add authentication for secure multi-user access

📥 Add CSV upload feature for batch predictions

🙋‍♂️ Author
Tushar Chaudhary
📧 Email: tushar@example.com
🔗 GitHub: github.com/TusharChaudhary

