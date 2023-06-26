# Heart Disease Prediction
### Abstract
Heart disease is a major health concern affecting individuals worldwide. Early detection and prediction of heart disease play a crucial role in providing timely medical interventions and improving patient outcomes. This project focuses on predicting heart disease based on various patient attributes using classification algorithms. Exploratory data analysis will be performed to gain insights into the data, and different classification models will be trained and evaluated using performance metrics to identify the most effective model.

### Problem Statement
The goal of this project is to predict whether a patient has heart disease or not based on their medical records. Various algorithms will be used to accomplish this task. Before building the model, exploratory data analysis will be conducted to understand the data and identify any patterns or relationships. The performance of each model will be evaluated using various metrics to assess their predictive capabilities.

### Dataset Information
The dataset consists of several predictor variables and one target variable, target. The target variable represents whether the patient has heart disease or not, with values 1 for 'Yes' and 0 for 'No'. 

The dataset includes the following columns:

1. age: Age of the patient
2. gender: Gender of the patient (0: Male, 1: Female)
3. chest_pain: Type of chest pain experienced by the patient (0, 1, 2, 3)
4. rest_bps: Blood pressure of the patient while resting (in mm/Hg)
5. cholesterol: Patient's cholesterol level (in mg/dl)
6. fasting_blood_sugar: Blood sugar of the patient while fasting (0: False, 1: True)
7. rest_ecg: Potassium level (0, 1, 2)
8. thalach: Maximum heart rate of the patient
9. exer_angina: Exercise-induced angina (1: Yes, 0: No)
10. old_peak: ST depression induced by exercise relative to rest
11. slope: Slope of the peak of the exercise ST-Segment (0, 1, 2)
12. ca: Number of major vessels (0, 1, 2, 3, 4)
13. thalassemia: Thalassemia blood disorder (0, 1, 2, 3)
14. target: Presence of heart disease (1: Yes, 0: No)

### Scope
This project will involve the following steps:<br>
**Data Pre-processing**: We will understand the basic structure and perform necessary data cleaning, handling missing values, handling duplicate values.<br>
**Exploratory Data Analysis (EDA)**: We will conduct an initial exploration of the dataset to perform Univariate, Bivariate, Multivariate Analysis and find patterns in the data. Also, we will treat outliers. <br>
**Training Models**: We have created user-defined functions which will ease our process of training dataset. We will train multiple Machine learning algorithms like Logistic Regression, Decision Tree, Random Forest, Bagging, AdaBoost, XGBoost, Naive Bayes, KNN, SVM with different tunning parameters to predict the likelihood of individuals in predicting heart disease based on the provided features.<br>
**Model Evaluation**: We will tabulate and evaluate the performance of all trained models using appropriate evaluation metrics and assess their predictive capabilities.<br>
**Learning Outcome**: Through this project, you will gain a better understanding of exploratory data analysis, data preprocessing, and knowledge of various machine learning algorithms. You will also develop skills in model evaluation, and drawing insights from the results.<br>

### Conclusion
By completing this project, you will gain practical experience in analyzing medical data, building classification models for heart disease prediction, and evaluating their performance using various metrics. You will also learn about exploratory data analysis, data preprocessing techniques, and all classification algorithms with its pruning techniques. This project will enhance your understanding of the relationships among variables and enable you to apply similar techniques in future predictive tasks. Predicting heart disease accurately can significantly improve patient care and outcomes, making this project both impactful and informative.
