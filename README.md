# week2-task1

## 📌 Project Title  
**Telco Customer Churn Prediction**

## 📝 Task Objective  
Build and evaluate machine learning models to predict customer churn using IBM’s Telco dataset. Implement preprocessing, model training (Logistic Regression and Random Forest), evaluation, hyperparameter tuning, and model saving.

---

## 📂 Dataset  
- **Name**: Telco Customer Churn  
- **Source**: [IBM Sample Dataset](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/)  
- **Description**: Contains customer demographics, services, account info, and churn status.

---

## 🔧 Tools & Libraries  
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## ⚙️ Steps Implemented

### 1. Data Loading & Exploration
- Load dataset using pandas  
- Inspect for missing values, data types, and basic statistics  

### 2. Data Preprocessing
- Handle missing values  
- Encode categorical features  
- Normalize/scale numerical columns  
- Use `ColumnTransformer` and `Pipeline` from scikit-learn  

### 3. Model Building
- Train two classification models:
  - **Logistic Regression** (baseline)  
  - **Random Forest Classifier** (ensemble model)

### 4. Model Evaluation
- Evaluate both models on test set using:
  - Accuracy  
  - Classification Report  
  - ROC-AUC Score  

### 5. Hyperparameter Tuning
- Use `GridSearchCV` to find the best hyperparameters for Random Forest  

### 6. Model Saving
- Save the best model using `joblib` as a `.pkl` file  

---

## 📊 Final Results
- **Best Model**: Tuned Random Forest Classifier  
- **Test AUC Score**: ~0.83  
- All performance metrics are detailed in the notebook.

---


