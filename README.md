# UNP_ML_CLASSIFICATION_PROJECT_ENGINEERING_GRADUATE_SALARY_PREDICTION_USING_PYTHON

Engineering Graduate Salary Prediction

1. Project Overview

I completed this project as part of my Data Science and Machine Learning Internship with United Network of Professionals (UNP), and it was carried out as a collaborative group project. The main objective was to predict whether an engineering graduate would receive a High Salary or Low Salary based on academic performance, aptitude scores, technical skills, and personality traits.

2. Dataset Description

The dataset contains 2,998 engineering graduate records and 34 attributes. It includes demographic details, academic scores, AMCAT aptitude scores, technical module scores, and personality traits.

3. Data Cleaning

We checked the dataset for missing values, duplicate records, and data inconsistencies. The dataset contained no missing values or duplicate records.

4. Data Preprocessing

We removed unnecessary columns, handled -1 values in technical scores, grouped engineering specializations into broader streams, and performed encoding on categorical variables. We also created the target variable, "SalaryClass", by dividing graduates into High Salary and Low Salary categories based on the average salary of ₹3,05,175.

5. Exploratory Data Analysis (EDA)

We performed exploratory data analysis using histograms, boxplots, scatterplots, and correlation heatmaps. This helped us understand the distribution of salaries and the relationship between academic performance, aptitude scores, college tiers, and salary categories.

6. Feature Analysis

We examined academic scores, aptitude scores, technical skills, and personality traits to understand their contribution to salary prediction. We also performed Variance Inflation Factor (VIF) analysis to identify multicollinearity among features.

7. Model Building

We implemented ten classification algorithms: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Machine, Gaussian Naive Bayes, AdaBoost, Gradient Boosting, XGBoost, and Artificial Neural Network (ANN).

8. Train-Test Splitting

We tested different train-test split ratios, including 80/20, 75/25, 70/30, and 60/40, to compare the performance of different classification models.

9. Model Evaluation

We evaluated the models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC Score. These metrics helped us compare the performance of the classification algorithms.

10. Artificial Neural Network (ANN)

We developed an Artificial Neural Network using multiple architectures. The best-performing architecture contained three hidden layers with 64, 32, and 16 neurons, achieving a test accuracy of approximately 73.83%.

11. Model Comparison

We compared all ten classification models across different train-test splits. XGBoost achieved the highest accuracy of approximately 74.67% with the 80/20 split, while Random Forest and Gradient Boosting also showed competitive performance.

12. Conclusion

The project helped us understand how academic performance, aptitude scores, technical skills, and other graduate attributes can be used to predict salary categories. Among the tested models, XGBoost delivered the best overall classification accuracy.

GOOGLE COLAB FILE LINK : https://drive.google.com/file/d/18cez4Eo0I2c9SuhfsGlMM7F6wn5aZp1m/view?usp=sharing

PROJECT PRESENTATION FILE LINK : https://drive.google.com/file/d/18cez4Eo0I2c9SuhfsGlMM7F6wn5aZp1m/view?usp=sharing
