# Heart Disease Prediction using Machine Learning

A logistic regression model that predicts heart disease with 85% accuracy, trained on clinical parameters from 303 patients.

##  Project Overview
This project analyzes cardiovascular health data to predict heart disease presence (1) or absence (0) using:
- 13 clinical features including age, cholesterol levels, blood pressure, etc.
- Logistic Regression algorithm
- 80-20 train-test split with stratification
- Achieves 85.12% training and 81.97% test accuracy

##  Dataset Information

**Source**: UCI Heart Disease Dataset (cleaned version)  
**Samples**: 303 patients  
**Features**: age, sex, cp (chest pain type), trestbps (resting blood pressure),
chol (cholesterol), fbs (fasting blood sugar), restecg (resting ECG),
thalach (max heart rate), exang (exercise induced angina),
oldpeak (ST depression), slope (ST segment slope),
ca (major vessels colored), thal (thalassemia type)

**Target**: 0 = Healthy, 1 = Heart Disease  
**Class Distribution**: 165 cases (54.5%) vs 138 healthy (45.5%)

## 🛠️ Installation & Usage

1. Clone repository:
```bash
git clone https://github.com/TiyaRajput123/Heart-Disease-Prediction.git
cd HeartDiseasePrediction
2.Install requirements:
pip install -r requirements.txt
3.Run Jupyter notebook:
jupyter notebook HeartDiseaseProject.ipynb
4.For predictions:
# Sample prediction (input format: age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca,thal)
input_data = [60,1,0,130,206,0,0,132,1,2.4,1,2,3]
prediction = model.predict([input_data])  # Returns 0 (Healthy) or 1 (Heart Disease)

📊 Model Performance
Metric	Score
Training Accuracy	85.12%
Test Accuracy	81.97%

 ##  **File Structure**

├── HeartDiseaseProject.ipynb      # Main analysis notebook
├── heart_disease_data.csv         # Dataset (303 samples)
├── README.md                      # This documentation
