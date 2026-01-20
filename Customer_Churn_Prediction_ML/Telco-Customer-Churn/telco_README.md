# Telco Customer Churn Prediction
This project is about predicting whether a telecom customer is likely to leave the service or not.  
I built this project to practice a complete **machine learning workflow** on a real-world dataset, starting from data understanding to model evaluation.

---

## Dataset Used
- **Telco Customer Churn Dataset**
- Contains customer details like:
  - Gender, tenure, contract type
  - Internet and phone services
  - Monthly and total charges
- Target column: **Churn (Yes / No)**

---

## Steps Followed in This Project

### 1. Understanding the Data
- Loaded the dataset and checked:
  - Number of rows and columns
  - Data types
  - Missing and incorrect values
- Understood what each column represents

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed how churn depends on:
  - Contract type
  - Tenure
  - Monthly charges
- Used basic plots to understand trends
- Observed that customers with **month-to-month contracts** churn more

---

### 3. Data Preprocessing
- Converted categorical columns into numerical form
- Handled data type issues
- Removed unnecessary columns like customer ID
- Split the data into **training and testing sets**

---

### 4. Model Building
Trained multiple classification models:
- Logistic Regression
- Decision Tree
- Random Forest

This helped compare simple and advanced models.

---

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy
  - Confusion matrix
  - Classification report
- Compared performance and selected the better model

---

## Key Learnings
- Tenure and contract type are strong churn indicators
- Ensemble models like Random Forest perform better
- Proper preprocessing improves model performance significantly

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Files
Telco-Customer-Churn-Prediction/

##### implementation_code.ipynb
##### Telco-Customer-Churn.csv
##### README.md


---

## Author
**Shreyash More**   