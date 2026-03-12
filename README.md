# Customer Churn Prediction

A web-based application that predicts **customer churn** using a **Machine Learning model** (Random Forest). Users can input customer information via a web form, and the app outputs whether the customer is likely to churn, along with a confidence score.

---

## 🚀 Features

- Predicts customer churn based on 19 input features:
  - Senior Citizen, Monthly Charges, Total Charges, Gender, Partner, Dependents
  - Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup
  - Device Protection, Tech Support, Streaming TV, Streaming Movies
  - Contract, Paperless Billing, Payment Method, Tenure
- Provides confidence score for predictions
- Clean and responsive **Bootstrap 5** UI
- Easily deployable with **Flask**

---

## 🛠 Tech Stack

- **Backend:** Python, Flask
- **Machine Learning:** scikit-learn (Random Forest)
- **Data Handling:** pandas
- **Frontend:** HTML, Bootstrap 5
- **Model Storage:** Pickle (`model.sav`)

---

## 📁 Folder Structure

customer-churn-prediction/
│
├─ app.py                   # Flask application
├─ model.sav                # Trained ML model (Pickle)
├─ first_telc.csv           # Dataset (optional if large, can ignore in Git)
├─ requirements.txt         # Python dependencies
├─ README.md                # Project documentation
├─ .gitignore               # To ignore unwanted files
│
├─ templates/
│   └─ home.html            # Flask HTML template
│
└─ images/              	# Any images used in your UI



# How It Works

User fills out the web form with customer data.

Flask backend collects the input and formats it into a DataFrame.

Input is preprocessed and passed into the trained Random Forest model.

Prediction is made (Churn or Not Churn) with probability confidence.

Result is displayed on the web page.

# Future Improvements

Add data validation for form inputs

Add charts to visualize churn probability

Switch to interactive dashboards using Plotly/Dash


