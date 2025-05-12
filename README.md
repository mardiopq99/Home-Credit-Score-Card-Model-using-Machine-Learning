# Home Credit Scorecard Modeling Project

## 📌 Overview

This project was developed as part of a final task during the Data Scientist Bootcamp at Rakamin Academy. It focuses on building a machine learning model to support **Home Credit Indonesia** in improving their **credit approval process** by predicting the likelihood of a customer defaulting on a loan.

By identifying high-risk applicants more accurately, the company can reduce default rates while still approving trustworthy customers — contributing to smarter and more inclusive financial services.

## 🎯 Objectives

- Develop predictive models to classify applicants by credit risk level.
- Support more accurate and efficient credit decision-making.
- Reduce default rates and increase approval for low-risk applicants.

## 📊 Business Metrics

- Default Rate Reduction
- Approval Rate of Low-Risk Applicants
- Model Accuracy, Precision, Recall

## 🧠 Key Insights

- **Top Numerical Features**: `EXT_SOURCE_1`, `EXT_SOURCE_2`, and `EXT_SOURCE_3` strongly distinguish default risk.
- **Risk Indicators**: Short employment duration, younger age, lack of assets (car/property), and low education level are correlated with higher default rates.
- **Model of Choice**: `XGBoost` was selected due to its balance of high performance and low computation time.

## 🔧 Technologies & Tools

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn

## 🛠️ Methodology

1. **Exploratory Data Analysis (EDA)**  
   Explored patterns in demographic, employment, and financial data to extract meaningful features.

2. **Data Preprocessing**  
   Cleaned missing values, encoded categorical variables, scaled numeric values, and handled imbalanced classes.

3. **Model Development**  
   Compared 4 models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost (chosen model)

4. **Evaluation Metrics**  
   Evaluated models on Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## ✅ Results

- **XGBoost** achieved the best balance of recall and accuracy without overfitting.
- Model is effective in identifying **low-risk borrowers** while remaining conservative in predicting defaulters.

## 💡 Business Recommendations

- Prioritize external score features and document completeness in the credit evaluation process.
- Consider demographic and job stability more than just financial metrics like loan amount or income.
- Continue model monitoring and retraining with updated data to improve predictions.

## 📁 Project Structure

📦home-credit-scorecard
┣ 📂notebooks
┣ 📂data
┣ 📜README.md
┣ 📜requirements.txt
┗ 📜modeling.py


## 👨‍💻 Author

**Mardio Edana Putra**  
Aspiring Data Analyst | Home Credit Indonesia  
📧 mardiopq@gmail.com  
📌 [LinkedIn](https://www.linkedin.com/in/mardiopq99)  
📌 [GitHub](https://github.com/mardiopq99)

---

*Thank you for visiting this project! Feel free to fork, open issues, or suggest improvements.*
