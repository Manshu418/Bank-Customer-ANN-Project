# Bank Customer Analytics Using Artificial Neural Networks (ANN)

This project contains two Machine Learning applications built using **Artificial Neural Networks (ANN)** and deployed using **Streamlit**.

The applications use the Bank Customer Churn dataset to perform two different tasks:

1. **Customer Churn Prediction (Classification):** Predicts whether a bank customer is likely to leave the bank.
2. **Estimated Salary Prediction (Regression):** Predicts a customer's estimated salary based on their personal and banking information.

## 🚀 Live Applications

- **Customer Churn Prediction:** [Launch App](https://bank-churn-classification-4akcjgvxle8uaxelqqd8ne.streamlit.app/)
- **Estimated Salary Prediction:** [Launch App](https://bank-salary-regression-4trczscnp8uibzpwamrtvk.streamlit.app/)

*The links will be added after deploying both applications on Streamlit Community Cloud.*

## 📊 Dataset

The project uses the **Bank Customer Churn Dataset (`Churn_Modelling.csv`)**.

The dataset contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Credit Card Status
- Active Membership Status
- Estimated Salary
- Exited (Churn Status)

## 🧠 Project 1: Customer Churn Prediction

This is a binary classification problem that predicts whether a customer will leave the bank.

**Target Variable:** `Exited`

- `0` – Customer stays with the bank.
- `1` – Customer leaves the bank.

### Technologies Used
- Artificial Neural Network (ANN)
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit

### Features
- Data preprocessing and feature encoding
- Feature scaling
- ANN model training
- Churn probability prediction
- Interactive Streamlit interface

## 📈 Project 2: Estimated Salary Prediction

This is a regression problem that predicts the estimated salary of a bank customer using their demographic and banking details.

**Target Variable:** `EstimatedSalary`

### Technologies Used
- Artificial Neural Network (ANN)
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit

### Features
- Data preprocessing and feature encoding
- Feature scaling
- ANN model training
- Salary prediction
- Interactive Streamlit interface

## 📁 Project Structure

```text
Bank-Customer-ANN-Project/
│
├── Classification/
│   ├── app.py
│   ├── classification_model.h5
│   ├── label_encoder_gender.pkl
│   ├── onehot_encoder_geo.pkl
│   ├── scaler.pkl
│   ├── experiments.ipynb
│   └── prediction.ipynb
│
├── Regression/
│   ├── streamlit_regression.py
│   ├── regression_model.h5
│   ├── label_encoder_gender.pkl
│   ├── onehot_encoder_geo.pkl
│   ├── scaler.pkl
│   ├── experiments.ipynb
│   ├── salaryregression.ipynb
│   └── hyperparametertuningann.ipynb
│
├── Churn_Modelling.csv
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Manshu418/Bank-Customer-ANN-Project.git
```

### 2. Navigate to the Project Directory

```bash
cd Bank-Customer-ANN-Project
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Applications Locally

### Customer Churn Prediction

```bash
streamlit run Classification/app.py
```

### Estimated Salary Prediction

```bash
streamlit run Regression/streamlit_regression.py
```

## ☁️ Deployment

Both applications are deployed independently using **Streamlit Community Cloud**, while sharing the same GitHub repository.

- Classification entry point: `Classification/app.py`
- Regression entry point: `Regression/streamlit_regression.py`

## 👨‍💻 Author

**Manshu**

GitHub: [@Manshu418](https://github.com/Manshu418)

---

⭐ If you find this project useful, consider giving the repository a star!
