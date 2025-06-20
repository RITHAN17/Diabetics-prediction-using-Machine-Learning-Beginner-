A machine learning model to predict diabetes using health parameters.
# 🩺 Diabetes Prediction using Machine Learning

This project uses supervised machine learning models to predict whether a person is diabetic based on medical attributes. It was developed as part of **Week 1 Task** during my internship at **[InternPe](https://www.linkedin.com/company/internpe/)**.

## 📊 Dataset
- **Source**: PIMA Indian Diabetes Dataset
- **Features used**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age

## 🤖 Machine Learning Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

## 🛠️ Technologies
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (optional for visualization)

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

## 🚀 How to Run
1. Clone this repository or download the files
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
  Dataset
  ## 📊 Dataset: PIMA Indian Diabetes Dataset

This dataset is used to predict the likelihood of diabetes in female patients of Pima Indian heritage, aged 21 and older. It contains several medical predictor variables and one target variable (`Outcome`).

### 🔢 Features:

| Feature                    | Description                                                   |
|---------------------------|---------------------------------------------------------------|
| Pregnancies               | Number of times the patient was pregnant                      |
| Glucose                   | Plasma glucose concentration after a 2-hour oral test         |
| BloodPressure             | Diastolic blood pressure (mm Hg)                              |
| SkinThickness             | Triceps skin fold thickness (mm)                              |
| Insulin                   | 2-Hour serum insulin (mu U/ml)                                |
| BMI                       | Body Mass Index (weight in kg / (height in m)^2)              |
| DiabetesPedigreeFunction  | A function that scores likelihood of diabetes based on family history |
| Age                       | Age of the patient (in years)                                 |
| Outcome                   | 0 = Non-diabetic, 1 = Diabetic                                |

### 📁 Source:
- National Institute of Diabetes and Digestive and Kidney Diseases  
- Publicly available on Kaggle: [Click here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
