# 📊 Customer Churn Analysis

## 🎯 Objective
Analyze customer churn behavior and identify key factors leading to customer attrition.

---

## 📂 Dataset
- Customer dataset containing features like:
  - Tenure
  - Support Calls
  - Subscription Type
  - Contract Length
  - Total Spend
  - Churn (Target Variable)

---

## 🧹 Data Cleaning
- Removed missing values
- Converted data types
- Handled categorical variables using encoding

---

## 📊 Exploratory Data Analysis

### Key Insights:
- Customers with **monthly contracts** show higher churn
- Customers with **high support calls** have significantly higher churn
- **Early tenure customers** are more likely to leave
- **Subscription type** has minimal impact on churn
- Customers who churn tend to have **lower spending**

---

## 🤖 Model
- Built a **Logistic Regression model**
- Used:
  - Train-test split
  - Feature encoding
  - Standard scaling

### 📈 Accuracy:
- ~89.6%

---

## 💡 Business Recommendations
- Focus on **retaining early-stage customers**
- Improve **customer support experience**
- Encourage **long-term contracts**
- Identify **low-engagement customers early**

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
