# Customer Churn Prediction using ANN

A machine learning project that predicts whether a bank customer is likely to churn using an **Artificial Neural Network (ANN)**. The trained model is integrated with **Streamlit** to provide an interactive web application.

## 🚀 Project Overview

Customer churn is an important problem for businesses. This project uses customer information to predict the probability of a customer leaving the bank.

The application takes customer details as input and provides:

* Churn probability
* Churn prediction
* Simple and interactive user interface

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* Scikit-learn
* Pandas
* NumPy
* Streamlit
* Pickle

## 📊 Features Used

The model uses the following customer information:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

## 🔄 Project Workflow

```text
Customer Data
     ↓
Data Preprocessing
     ↓
Label Encoding
     ↓
One-Hot Encoding
     ↓
Feature Scaling
     ↓
ANN Model
     ↓
Model Training
     ↓
Model Saving
     ↓
Streamlit Application
     ↓
Churn Prediction
```

## 🧠 Machine Learning

An **Artificial Neural Network (ANN)** is used to classify customers based on their likelihood of churning.

The project uses:

* `LabelEncoder` for Gender
* `OneHotEncoder` for Geography
* `StandardScaler` for feature scaling
* TensorFlow/Keras for building and training the ANN

The trained model and preprocessing objects are saved using Pickle and Keras.

## 📁 Project Structure

```text
ANN-Project/
│
├── app.py
├── experiments.ipynb
├── prediction.ipynb
├── Churn_Modelling.csv
│
├── model.h5
├── onehot_encoder_geo.pkl
├── label_encoder_gender.pkl
├── scaler.pkl
│
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-prediction-ann.git
```

### 2. Navigate to the project

```bash
cd customer-churn-prediction-ann
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install the required packages

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Run the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your browser.

## 📈 Example

The user enters customer information such as:

```text
Geography: Germany
Gender: Female
Age: 45
Balance: 120000
Credit Score: 550
Estimated Salary: 60000
Tenure: 2
Number of Products: 1
Has Credit Card: 1
Is Active Member: 0
```

The application then generates a churn probability and predicts whether the customer is likely to churn.

## 📚 Notebooks

### `experiments.ipynb`

Contains the data analysis, preprocessing, model building, training, and experimentation.

### `prediction.ipynb`

Contains the prediction workflow and testing of the trained model.

## 🎯 Project Objective

The objective of this project is to build an end-to-end AI/ML application that can identify customers who are at risk of churning.

This can help businesses take proactive steps to improve customer retention.

## 🔮 Future Improvements

* Improve model performance through hyperparameter tuning
* Add model evaluation visualizations
* Deploy the application online
* Add more customer insights
* Compare ANN with other machine learning algorithms

## 👨‍💻 Author

**Kodeeswaran A.S.**

AI/ML Enthusiast | Software Developer | Cybersecurity Enthusiast

---

⭐ If you find this project useful, consider giving the repository a star!
