# Students Performance Prediction

## Project Overview

This project aims to predict students' scores in mathematics, reading, and writing based on their demographic details and other relevant features, such as gender, race/ethnicity, parental education level, lunch type, and test preparation course completion. By analyzing these factors, the project provides insights into how these characteristics influence academic achievement and offers potential strategies for improving student outcomes.

### Dataset

The dataset contains information on students' backgrounds and their academic performance in three subjects: mathematics, reading, and writing. The attributes in the dataset include:

1. Gender: The student's gender
2. Race/Ethnicity: The racial or ethnic group the student belongs to
3. Parental Level of Education: The highest educational level attained by the student's parents or guardians
4. Lunch: Type of lunch the student receives (standard, free/reduced)
5. Test Preparation Course: Whether the student completed a test preparation course
6. Math Score: Performance on math assessments
7. Reading Score: Performance on reading assessments
8. Writing Score: Performance on writing evaluations

Dataset URL: [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

## Problem Statement

The objective of this project is to examine the factors that impact students' academic achievement and develop a model to predict scores in math, reading, and writing based on these factors. The analysis can help educators and policymakers implement interventions tailored to improving student outcomes. Additionally, the predictive model can identify at-risk students and assist in devising personalized strategies to boost performance.

## Models Used

- Linear Regression: A basic regression model used for prediction, providing insights into the relationship between input features and student scores.
- Random Forest: A robust machine learning model used for prediction, offering improved accuracy and flexibility compared to linear regression.
- Gradient Boosting: A powerful ensemble method that builds strong predictive models through the sequential correction of errors made by weak models.

## Results

- Linear Regression:
  - Train MSE: 1.13e-28
  - Test MSE: 9.65e-29
  
- **Random Forest**:
  - Train MSE: 0.105
  - Test MSE: 0.414
  
- **Gradient Boosting**:
  - Train MSE: 0.148
  - Test MSE: 0.303

## Conclusion

The Ridge Regression model fits the data extremely well, explaining nearly all the variation in both the training and testing datasets. It offers very accurate predictions with minimal average errors between predicted and actual values. The Random Forest and Gradient Boosting models also provide reliable results, though with slightly higher test MSE values, suggesting they generalize well to unseen data but leave room for improvement.

This project helps understand how demographic and behavioral factors influence academic performance and provides a basis for targeted educational interventions.
