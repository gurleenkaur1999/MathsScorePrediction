# Student Performance
Predict student performance in secondary education (high school)

This project predicts the final math scores (G3) of students based on features like previous grades, study habits, and demographic data. It uses linear regression and evaluates model performance using RMSE, MAE, and R².

## Dataset
The dataset includes:

- Student grades: G1, G2, G3
- Demographic features: age, sex, family background
- Study-related features: study time, number of failures, extra-curricular activities
- Other social features: absences, health, and more

Data source: [Cortez and Silva, 2008](https://archive.ics.uci.edu/ml/datasets/student+performance)

## Features Used
- G1, G2: Previous grades
- Study time
- Number of failures
- Absences
- Extra-curricular activities
- Demographics: age, sex, family size

## Methodology
1. **Data preprocessing**
   - Handle missing values
   - Encode categorical features
   - Scale numerical features

2. **Modeling**
   - Split dataset into training and test sets
   - Train Linear Regression model

3. **Evaluation**
   - Metrics used: RMSE, MAE, R²

## Results
MSE: 1.98
MAE: 1.28
R²: 0.75


