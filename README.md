# 📊 Customer Churn Prediction using Machine Learning


## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Losing existing customers directly impacts revenue and business growth.

This project uses **Machine Learning** to predict whether a telecom customer is likely to **leave (churn)** or **continue** using the service. The prediction is made based on customer demographics, subscription details, and service usage.

The project includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Engineering
- Machine Learning Model Training
- Flask Web Application for Prediction

---

## 🎯 Problem Statement

Develop a machine learning model that predicts customer churn using historical telecom customer data. The web application allows users to enter customer details and instantly receive a churn prediction along with the model's confidence score.

---

# 🚀 Features

- 📈 Customer Churn Prediction
- 🤖 Random Forest Classifier
- 🌐 Flask Web Application
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Preprocessing
- 🔍 Feature Engineering
- 📋 User-Friendly Web Interface
- ⚡ Instant Prediction with Confidence Score

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Web Framework | Flask |
| Machine Learning | Scikit-Learn |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Frontend | HTML, Bootstrap |
| Notebook | Jupyter Notebook |

---

# 📂 Project Structure

```
Customer-Churn-Predication/

│── app.py
│── model.sav
│── requirements.txt
│── README.md
│── .gitignore

├── data
│     ├── first_telc.csv
│     ├── tel_churn.csv
│     └── WA_Fn-UseC_-Telco-Customer-Churn.csv

├── notebooks
│     ├── Churn Analysis - EDA.ipynb
│     └── Churn Analysis - Model Building.ipynb

├── templates
│     └── home.html

└── screenshots
```

---

# 📊 Dataset

Dataset Used:

**Telco Customer Churn Dataset**

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Phone Service
- Internet Service
- Online Security
- Device Protection
- Tech Support
- Contract Type
- Monthly Charges
- Total Charges
- Tenure
- Payment Method

Target Variable:

**Churn**
- Yes
- No

---

# ⚙ Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. One-Hot Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Saving
10. Flask Deployment

---

# 🤖 Machine Learning Model

Algorithm Used:

- Random Forest Classifier

The trained model predicts whether a customer is likely to churn based on the provided input features.

---

# 🌐 Web Application

The Flask application provides an easy-to-use interface where users can:

- Enter customer details
- Submit the form
- Receive churn prediction
- View confidence score

---

# 📸 Screenshots

## Home Page

> Add screenshot here

```
screenshots/home.png
```

## Prediction Result

> Add screenshot here

```
screenshots/result.png
```

## Exploratory Data Analysis

> Add EDA visualization screenshots here

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/riya119215/Customer-Churn-Predication.git
```

Move into the project directory

```bash
cd Customer-Churn-Predication
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

---

# 📦 Required Libraries

- Flask
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# 🔮 Future Improvements

- Deploy the application on Render
- Improve UI using Bootstrap 5
- Add Login Authentication
- Support Batch Prediction
- Add Model Explainability using SHAP
- Compare Multiple ML Models
- Improve Prediction Accuracy
- Build REST API

---

# 👩‍💻 Author

**Riya Patel**

### GitHub

https://github.com/riya119215

### Kaggle

https://www.kaggle.com/riyapatel1903

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

It motivates me to build more Machine Learning and AI projects.

---

## 📧 Contact

For suggestions or collaboration, feel free to connect through GitHub or Kaggle.

---

## 📄 License

This project is licensed under the MIT License.