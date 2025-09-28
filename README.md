# Loan-Approval-Prediction-Supervised-Learning-
This project applies machine learning classification techniques to predict whether a loan application will be approved or not, based on applicant details such as income, credit history, loan amount, and more.

📌 Project Overview

Loan approval is a critical process for banks and financial institutions. Automating this using ML models can reduce manual work and improve decision-making.

The project includes:

Data cleaning & preprocessing.
Exploratory Data Analysis (EDA).
Feature engineering.

Model training with supervised ML algorithms:

Model evaluation with accuracy, confusion matrix, and classification report.

⚙️ Technologies Used:

Python 🐍,
Pandas, NumPy → data preprocessing.
Matplotlib, Seaborn → visualization.
Scikit-learn → ML models & evaluation.

🚀 Workflow

Data Preprocessing

Handle missing values

Encode categorical variables (e.g., Gender, Marital Status)

Normalize numeric features if required

EDA

Visualized loan approval distribution

Checked correlations between applicant details and approval status

Modeling

Tried multiple classifiers:

Logistic Regression

Decision Tree

Support Vector Machine (SVM)

Gaussian Naive Bayes.

Compared performance on accuracy & confusion matrix.

Evaluation

Confusion Matrix, Precision, Recall, F1-Score

ROC-AUC (if applicable)

📊 Results

Best performing model: 

Logistic Regression and Gaussian Naïve Bayes achieved 100% accuracy, with perfect precision, recall, and F1-score across both classes.

KNN and SVC also performed extremely well, with 99% accuracy and only a very small drop in recall/precision for one class.

All four algorithms show that the dataset is highly linearly separable and relatively easy to classify, leading to near-perfect performance.
