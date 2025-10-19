# 🩺 Diabetes Detection using Machine Learning

### 📘 Project Overview
This project predicts the likelihood of diabetes in patients based on various health indicators such as glucose level, BMI, age, blood pressure, and lifestyle factors.  
It applies multiple machine learning algorithms — **Logistic Regression**, **Random Forest**, and **XGBoost** — to analyze patient health data and classify whether an individual is likely to have diabetes.

The repository demonstrates a **complete end-to-end machine learning workflow**, including:
- Data loading and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering and encoding  
- Model training and hyperparameter tuning  
- Model evaluation and comparison  
- Model saving and deployment (Streamlit app)

---

### 🧩 Dataset
**File:** `diabetes_prediction_dataset.csv`  
Each row represents a patient’s health record with the following features:

| Feature | Description |
|----------|--------------|
| `gender` | Gender of the patient |
| `age` | Age of the patient |
| `hypertension` | 0 = No, 1 = Yes |
| `heart_disease` | 0 = No, 1 = Yes |
| `smoking_history` | Smoking habits (never, current, etc.) |
| `bmi` | Body Mass Index |
| `HbA1c_level` | Average blood sugar (HbA1c) |
| `blood_glucose_level` | Glucose level in blood |
| `diabetes` | Target variable (0 = Non-diabetic, 1 = Diabetic) |

**Dataset Source:** [Kaggle – Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

---

### ⚙️ Technologies Used
- **Python**
- **NumPy, Pandas** — Data manipulation  
- **Matplotlib, Seaborn** — Visualization  
- **Scikit-learn** — ML model development  
- **XGBoost** — Advanced gradient boosting classifier  
- **Streamlit** — Web app deployment  
- **Joblib** — Model saving/loading  

---

### 🧠 Machine Learning Models
| Model | Accuracy | Notes |
|--------|-----------|-------|
| Logistic Regression | ~85% | Interpretable baseline model |
| Random Forest | ~90% | Handles non-linearity well |
| XGBoost | ~92% | Best performing model |

*(Performance may vary depending on preprocessing and hyperparameters.)*

---

### 🧪 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC Score  
- Confusion Matrix  
- ROC Curve Visualisation  

---

### 🚀 How to Run the Project

#### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/diabetes-detection-ml.git
cd diabetes-detection-ml
