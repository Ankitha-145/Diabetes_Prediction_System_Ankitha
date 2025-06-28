# Diabetes_Prediction_System_Ankitha
A machine learning project to predict diabetes using Support Vector Machine (SVM), with real-time input prediction and model evaluation.
# Diabetes Prediction using SVM

A machine learning model that predicts whether a person is diabetic based on medical data, using Support Vector Machine (SVM) with a linear kernel.

## Features Used
- Glucose, Blood Pressure, Insulin, BMI, Age, etc.
- Output: 0 (Non-Diabetic), 1 (Diabetic)

##  Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (SVM, StandardScaler)
- Matplotlib, Seaborn

## Workflow
- Data preprocessing and scaling
- Train-test split
- SVM model training and evaluation
- Real-time prediction system for new input

## Sample Prediction
```python
input_data = (5,166,72,19,175,25.8,0.587,51)
# Predicts: The person HAS diabetes
