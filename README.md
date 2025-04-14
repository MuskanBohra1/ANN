# **Telco Customer Churn Prediction Using Artificial Neural Network (ANN)**

## **Project Overview**
This project uses an **Artificial Neural Network (ANN)** to predict customer churn in the telecommunications industry. The goal is to classify customers as likely to churn or stay, helping telecom companies implement proactive retention strategies.

---

## **Dataset Description**
The **Telco Customer Churn Dataset** contains **7,043** customer records with **21 features**, including demographics, service details, and billing information. The target variable is **Churn**, indicating whether a customer has left the service.

---

## **Project Methodology**

### 1. **Data Preprocessing**
   - Handled missing values using median imputation.
   - Categorical variables were encoded using label encoding and one-hot encoding.
   - Continuous features were scaled using `StandardScaler`.

### 2. **Exploratory Data Analysis (EDA)**
   - Higher churn rates were found in customers with month-to-month contracts and those with higher monthly charges.
   
### 3. **Model Development**
   - The ANN model had an input layer of 42 features, two hidden layers (128 and 64 neurons), and a sigmoid output for binary classification.
   - **Accuracy**: 83.6%, **Precision**: 78.4%, **Recall**: 69.2%, **F1-Score**: 73.5%.

---

## **Key Insights**

- **Retention Strategy**: Customers with month-to-month contracts are more likely to churn. Loyalty programs and discounts can help retain this group.
- **Service Improvement**: Offering services like **TechSupport** and **OnlineSecurity** can reduce churn.
- **Contract Strategy**: Promoting longer-term contracts lowers churn rates.
- **Revenue Impact**: Retaining just 10% of churners can save telecom companies significant revenue.

