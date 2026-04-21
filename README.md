# 📊 Credit Card Default Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting whether a credit card customer will default on their payment in the next month using machine learning techniques. The goal is to help financial institutions identify high-risk customers and reduce potential losses.

---

## 📂 Dataset
The dataset used is the **UCI Credit Card Default Dataset**, which contains information on 30,000 customers.

🔗 Dataset Link:  
https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients  

### Features include:
- Demographic details (Age, Gender, Education, etc.)
- Credit limit (LIMIT_BAL)
- Repayment history (PAY_0 to PAY_6)
- Billing amounts (BILL_AMT1 to BILL_AMT6)
- Payment amounts (PAY_AMT1 to PAY_AMT6)

**Target Variable:**  
`default.payment.next.month`  
- 0 → No Default  
- 1 → Default  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Removed unnecessary columns (ID)
- Handled class imbalance using **SMOTE**
- Applied **feature scaling (StandardScaler)**

### 2. Exploratory Data Analysis (EDA)
- Data distribution analysis
- Correlation heatmap
- Feature relationship analysis

### 3. Machine Learning Models
The following models were implemented:
- Logistic Regression  
- Decision Tree  
- K-Nearest Neighbours (KNN)  
- Support Vector Machine (SVM)  
- Random Forest  
- XGBoost  
- LightGBM  
- CatBoost  
- Voting Classifier  

### 4. Hyperparameter Tuning
- Applied **GridSearchCV** for Random Forest
- Optimized parameters to improve model performance

---

## 📈 Evaluation Metrics
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

---

## 🏆 Results
- **Tuned Random Forest** achieved the highest accuracy (~81.72%)
- **CatBoost and XGBoost** performed better in detecting defaulters (higher recall)
- Feature importance showed **repayment history** as the most critical factor

---

## ⚠️ Challenges
- Class imbalance in dataset  
- Complex customer behaviour  
- Feature selection and data quality  
- Model evaluation limitations  

---

## 🔮 Future Work
- Apply deep learning models  
- Use real-time financial data  
- Improve feature engineering  
- Explore advanced imbalance handling techniques  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- LightGBM  
- CatBoost  
- Matplotlib  
- Seaborn  


