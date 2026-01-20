# Customer Churn Prediction using Machine Learning
This project focuses on predicting whether a customer will **leave the bank (churn)** based on their personal, account, and transaction details.  
I built this project to understand the **end-to-end machine learning workflow**, from data analysis to model evaluation, using a real dataset.

---

## Dataset Used
- **Bank Customer Churn Dataset**
- Contains customer information such as:
  - Credit score
  - Age, gender
  - Balance, number of products
  - Active membership status
- Target column: **Exited** (1 = Churned, 0 = Not Churned)

---

## Project Structure
Customer-Churn-Prediction/

##### implementation_code.ipynb
##### Bank-Customer-Churn.csv
##### README.md

---

## Steps Followed to Complete This Project

### 1. Data Loading & Understanding
- Loaded the CSV file using Pandas
- Checked:
  - Shape of the dataset
  - Column names and data types
  - Missing and duplicate values
- Understood the meaning of each feature

---

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Studied how churn depends on:
  - Age
  - Balance
  - Credit score
  - Active membership
- Identified patterns affecting customer churn

---

### 3. Data Preprocessing
- Converted categorical variables into numerical format
- Removed unnecessary columns like customer ID
- Scaled numerical features where required
- Split the data into **training and testing sets**

---

### 4. Model Building
- Trained machine learning classification models such as:
  - Logistic Regression
  - Other suitable classifiers for comparison
- Focused on understanding model behavior rather than just accuracy

---

### 5. Model Evaluation
- Evaluated models using:
  - Accuracy score
  - Confusion matrix
  - Classification report
- Compared results to select the better performing model

---

## Key Insights
- Older customers show a higher churn rate
- Customers with low engagement are more likely to churn
- Feature preprocessing plays a major role in model performance

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## What I Learned
- Handling real-world structured data
- Performing meaningful EDA before modeling
- Building and evaluating ML classification models
- Understanding customer behavior through data

---

## Author
**Shreyash More**  