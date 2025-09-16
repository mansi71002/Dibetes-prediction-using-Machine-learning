# Dibetes-prediction-using-Machine-learning
# 🧠 Diabetes Prediction using Machine Learning

## 📝 Project Overview
This project focuses on predicting the likelihood of diabetes in patients using **Machine Learning models**.  
The model leverages the **Pima Indians Diabetes Dataset** to classify whether a patient is diabetic (`1`) or not (`0`) based on medical attributes.

---

## 📂 Dataset
- **Source:** [Pima Indians Diabetes Dataset (Kaggle/UCI)](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Features:**  
  - Pregnancies  
  - Glucose  
  - Blood Pressure  
  - Skin Thickness  
  - Insulin  
  - BMI  
  - Diabetes Pedigree Function  
  - Age  
- **Target:** Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## ⚙️ Project Workflow
1. **Data Preprocessing**
   - Handled missing values & outliers  
   - Standardized features using `StandardScaler`  

2. **Exploratory Data Analysis (EDA)**
   - Visualized distributions & feature correlations using `Matplotlib` and `Seaborn`  

3. **Model Building**
   - Algorithms used: Logistic Regression, Random Forest, SVM, KNN  
   - Hyperparameter tuning with `GridSearchCV`  

4. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Best model achieved **~80% accuracy**  

---

## 🧰 Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Scikit-learn** (ML models & evaluation)  
- **Jupyter Notebook**  

---

## 📌 Results
- Developed a robust model to predict diabetes with good precision and recall  
- Highlighted key predictors such as **Glucose, BMI, and Age**  
- Early prediction can assist healthcare professionals in decision-making  

