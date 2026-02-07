##### HEART-DISEASE
Heart Disease Prediction – Machine Learning Project
Overview
This project predicts whether a person is at risk of heart disease using different medical features such as age, sex, chest pain type, blood pressure, cholesterol, etc.
The goal is to build a machine learning model that can help in early detection of heart disease using data-driven analysis.
📊 Dataset
Source: Public Kaggle Heart Disease Dataset
Rows: 303
Columns: 14 medical features
Key Columns
age – Age in years
sex – Male/Female
cp – Chest pain type
trestbps – Resting blood pressure
chol – Serum cholesterol
fbs – Fasting blood sugar
thalach – Maximum heart rate
target – 1 = Heart Disease present, 0 = No disease
 Data Cleaning & Preprocessing
Checked missing values
Removed duplicates
Converted categorical columns using Label Encoding
Scaled numerical data (StandardScaler)
Analyzed distributions and correlations
Visualized outliers using boxplots
📈 Exploratory Data Analysis (EDA)
Key Patterns Identified:
Patients aged 40–60 have the highest risk.
Higher cholesterol and lower max heart rate strongly correlate with heart disease.
Chest pain type cp = 1 shows a strong link with disease presence.
Male patients show slightly higher risk than female patients.
Visualizations Used:
Histogram of numeric features
Correlation heatmap
Countplot of chest pain types
Distribution plot of age
Pairplot to visualize relationships
Machine Learning Models Tested
Model
Accuracy
Logistic Regression
85%
Random Forest
90%
K-Nearest Neighbors
83%
SVM
88%
✔ Best Model: Random Forest Classifier
Provided highest accuracy
Handles non-linear patterns well
Robust to outliers
 Conclusion
This machine learning model can predict heart disease with high accuracy after proper preprocessing and feature encoding.
The project demonstrates:
Data cleaning
EDA
Feature engineering
Model training & evaluation
Visual insights
This is an excellent end-to-end ML project for a Data Analyst / ML beginner portfolio.
Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook / Google Colab
