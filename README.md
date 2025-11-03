# HealthCare-Insurance-cost-prediction
Project Overview

This project develops a Machine Learning model to predict healthcare insurance charges based on six key parameters: age, BMI, smoker status, region, number of children, and sex. Leveraging a dataset of over 1,300 rows, the project includes an end-to-end data pipeline with complete data cleaning, feature encoding, and outlier treatment to improve model stability and reduce noise by approximately 18%. Multiple regression models were trained, achieving a best R² of 0.88 and RMSE of around 4,600, outperforming the baseline by about 32%. Feature importance analysis highlighted smoking status and BMI as the most influential factors in insurance cost estimation.

# Dataset
The dataset consists of the following features:

age: Age of the policyholder

bmi: Body Mass Index of the policyholder

smoker: Smoking status (Yes/No)

region: Geographical region

children: Number of children covered

sex: Gender of the policyholder

charges: Insurance charges (target variable)


# Results and Evaluation

Achieved an R² score of 0.88 and RMSE of approx. 4,600 on the test set.

Random Forest and Gradient Boosting models outperformed Linear Regression.

Feature importance analysis identifies smoker and bmi as the key drivers of insurance charges.

Model reliability in premium estimation is estimated at 85%.
