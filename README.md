# 🩺 Diabetes Prediction 🧠

Predicts the likelihood of diabetes using machine learning algorithms with the PIMA Indians Diabetes dataset.

---

## 🧪 Project Overview

This project follows a standard data science workflow:

1. **Data Loading & Exploration**  
   - Loaded the PIMA dataset  
   - Inspected structure, data types, null/missing values

2. **Data Preprocessing**  
   - Handled missing/zero values in key features (Glucose, BP, BMI, etc.)  
   - Scaled continuous features using StandardScaler

3. **Feature Selection & Visualization**  
   - Analyzed feature distributions and correlations  
   - Visualized key relationships (e.g., Glucose vs. Outcome)

4. **Model Building & Evaluation**  
   - Trained multiple classifiers:
     - Logistic Regression  
     - Support Vector Machine (SVM)  

5. **Final Model & Prediction**  
   - Chose best-performing model (SVM)  
   - Implemented predictions with user-input features

---

## 📂 Dataset Details

| Feature                   | Description                        |
|---------------------------|------------------------------------|
| Pregnancies               | Number of pregnancies              |
| Glucose                   | Blood glucose level, fasting       |
| BloodPressure             | Diastolic blood pressure           |
| SkinThickness             | Triceps skin fold thickness        |
| Insulin                   | 2-Hour serum insulin               |
| BMI                       | Body mass index                    |
| DiabetesPedigreeFunction  | Genetic diabetes risk function     |
| Age                       | Age in years                       |
| Outcome                   | 0 = No diabetes, 1 = Diabetes      |

**Source**: PIMA Indians Diabetes Database (UCI)

---

## 🔧 Technologies & Libraries

- **Python 3.x**  
- **Data handling**: pandas, numpy  
- **Visualization**: matplotlib, seaborn  
- **Machine Learning**: scikit-learn  
- **Interactive Analysis**: Google Colab

---

## 📈 Model Performance

- Best model: **Support Vector Machine** (or whichever you selected)  
- Metrics achieved:
  - Accuracy: 96 
  - Precision: 96  


---

## 🚀 Running the Project

1. Clone the repo:
   ```bash
      
   git clone https://github.com/visheshjain392/Diebetes-Prediction.git
   cd Diebetes-Prediction
