# 📞 Telecom Churn Prediction

Predicting customer churn is critical for telecom companies aiming to retain valuable customers and reduce revenue loss. This project builds a machine learning pipeline to analyze telecom customer data and predict the likelihood of churn, using a Logistic Regression model and advanced preprocessing techniques.

---

## 🚀 Project Overview

- **Goal:** Predict which customers are likely to churn based on their usage and account features.
- **Techniques:**  
  - Data preprocessing and feature selection  
  - Handling class imbalance with SMOTE  
  - Logistic Regression modeling  
  - Feature importance analysis  
  - Model evaluation (accuracy, confusion matrix, classification report)

---

## 📂 Dataset
**Source:**
- **Rows:** 3,333
- **Features:** 11 (including Churn, AccountWeeks, ContractRenewal, DataPlan, DataUsage, CustServCalls, DayMins, DayCalls, MonthlyCharge, OverageFee, RoamMins)

---
## Project Notebook
[telecom_churn.csv](https://github.com/user-attachments/files/20064752/telecom_churn.csv)

## 🛠️ Project Structure

---

## 📊 Key Steps

1. **Data Preprocessing**
   - Handle missing values 
   - Encode categorical variables
   - Scale features

2. **Class Imbalance Handling**
   - Stratified train-test split
   - Synthetic Minority Oversampling Technique (SMOTE)

3. **Modeling**
   - Logistic Regression (with class_weight and/or SMOTE)
   - Feature importance analysis

4. **Evaluation**
   - Accuracy, Confusion Matrix, Classification Report

---

## 🖼️ Example Visualizations

![Feature Importance](images/feature_importance.png)
![output](https://github.com/user-attachments/assets/90054d9d-4a26-4f9d-af55-c04bc8eaf4fc)
* Feature Importance using Linear Regression Model
  ![output1](https://github.com/user-attachments/assets/3edb759d-2d07-4bfc-8059-61ac82fd96b4)
  * Feature Importance using XGBOOST Model



## ⚙️ Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn


---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

For questions or feedback, please open an issue or contact [maleshanemorolong@example.com].

---

*Empowering telecoms with data-driven retention strategies!*



---

## 🏁 Getting Started

### 1. Clone the repository

