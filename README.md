# 🧠 Customer Churn Prediction using ANN

This project is built to predict whether a customer will churn or not using an Artificial Neural Network (ANN). Early identification of at-risk customers helps companies take proactive steps to retain them.

## 📌 Objective

To build and train an ANN model that classifies customers as likely to churn (`Exited = 1`) or not (`Exited = 0`) based on demographic and account data.

---

## 📂 Dataset Details

- **Filename**: `Churn_Modelling.csv`
- **Records**: 10,000
- **Features**:
  - `CreditScore`
  - `Geography`
  - `Gender`
  - `Age`
  - `Tenure`
  - `Balance`
  - `NumOfProducts`
  - `HasCrCard`
  - `IsActiveMember`
  - `EstimatedSalary`
- **Target**: `Exited` (1 = churned, 0 = stayed)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for preprocessing)
- TensorFlow / Keras (for ANN model)

---

## 🧪 Model Architecture

- **Input Layer**: Preprocessed numerical/categorical features
- **Hidden Layers**: 2-3 Dense layers with ReLU activation
- **Output Layer**: Sigmoid activation for binary classification
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam

---
