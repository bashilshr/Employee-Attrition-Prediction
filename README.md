Employee Attrition Prediction
This project focuses on building a machine learning-based system to predict employee attrition using HR analytics data. The goal is to identify patterns and key factors that lead to employee churn and help companies retain valuable talent.

📌 Project Overview
Objective: Predict whether an employee will leave the company.

Type: Supervised Classification Problem

Dataset: IBM HR Analytics Employee Attrition & Performance dataset

Target Variable: Attrition (Yes/No)

🔍 Features Used
Key features considered in the prediction include:

Age, Job Role, Monthly Income

Job Satisfaction, Environment Satisfaction

Years at Company, OverTime

Department, Business Travel

And more HR-related attributes

🧠 Machine Learning Models Used
The following models were evaluated:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Model performance was evaluated using:

Accuracy

Confusion Matrix

Classification Report

ROC-AUC Curve

🛠️ Tech Stack
Language: Python

Libraries:

pandas, numpy

matplotlib, seaborn

scikit-learn

xgboost

📊 Data Preprocessing
Handling categorical and numerical features

Encoding categorical variables

Feature selection and scaling

Train-test split

✅ Results
Best model: Random Forest (or whichever was best in your case)

Achieved accuracy of approximately XX% (replace with your result)

Important features: OverTime, JobSatisfaction, MonthlyIncome, etc.

📁 How to Run
Clone the repository:

git clone https://github.com/bashilshr/employee-attrition-prediction.git
cd employee-attrition-prediction

Install dependencies:
pip install -r requirements.txt

Run the Jupyter notebook:
jupyter notebook Employee_Attrition.ipynb

📌 Future Work
Hyperparameter tuning

Use of ensemble models

Deployment using Flask or Streamlit

Integration into HR dashboards

🧑‍💻 Author
Bashil Shrestha

