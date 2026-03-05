# 🩺 Diabetes Prediction using Logistic Regression

## 📌 Project Overview
This project predicts whether a person has diabetes based on medical diagnostic measurements.  
The model is trained using the Logistic Regression algorithm from Scikit-learn.

The dataset used is the **Pima Indians Diabetes Dataset**.

---

## 📊 Dataset Information
The dataset contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target Variable:
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (optional for visualization)

---

## ⚙️ Project Workflow

1. Load the dataset
2. Data preprocessing
3. Split data into training and testing sets
4. Train model using Logistic Regression
5. Evaluate model accuracy
6. Predict outcome for new input data

---

## 🚀 Model Training

```python
from sklearn.linear_model import LogisticRegression
model = LogisticRegression()
model.fit(X_train, y_train)
