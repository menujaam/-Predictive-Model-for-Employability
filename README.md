# IE0005-Predictive-Model-for-Employability
Overview
This project develops a machine learning model to predict the employability of job applicants based on demographic, educational, and professional backgrounds, as well as skills and experience. The dataset used is "Employability Classification of Over 70,000 Job Applicants".

Our Goals:
1. Improve recruitment efficiency
2. Enhance candidate selection accuracy
3. Identify and mitigate bias in hiring processes

Process:
1. Data Preparation

We removed irrelevant variables such as Unnamed and Previous Salary.

One-hot encoding for categorical variables

Univariate prediction to assess each predictor’s individual predictive power
2. Exploratory Data Analysis (EDA)
We visualised the data using countplot, boxplot, catplot. We found that Computer Skills and Country as strong predictors, with moderate influence from YearsCodePro and Education. We noted that “willingness to travel” had little impact on employment outcomes


3. Modeling

Compared Logistic Regression, Decision Tree, and Random Forest

Logistic Regression with multiple predictors achieved the best overall performance (accuracy, precision, recall, F1-score)

Multiple predictors performed better than using only the top feature (ComputerSkills)

4. Fairness & Bias Mitigation

Detected bias in gender, age, and education using fairness metrics and heatmaps

Applied Fairness Constraint, Rejection Option Classification, and Random Forest Classifier to reduce bias

Post-mitigation, Demographic Parity Difference and Equalized Odds Difference approached 0

5. Ethical Considerations

Emphasized the need for equity, transparency, and ongoing monitoring in hiring algorithms


