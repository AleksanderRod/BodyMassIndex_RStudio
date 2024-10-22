
## Project Summary: BMI and Obesity Analysis with Machine Learning

This project aims to analyze factors influencing Body Mass Index (BMI) and to leverage **machine learning** models to predict BMI levels. Using a dataset from Kaggle, we performed data cleaning in Excel and comprehensive analysis in RStudio, applying statistical tests like Correlation Tests, T-tests, and ANOVA to identify variables significantly associated with BMI. Key factors, such as high-calorie intake, physical activity, and family history of obesity, were explored and their relationship to BMI was established.

A significant aspect of the project involved building and evaluating **machine learning models** to predict BMI. We utilized **Linear Regression**, **Support Vector Machines (SVM)**, and **Random Forest** models to predict BMI based on selected variables. The models were trained and tested on the dataset, and their performance was evaluated using metrics like RMSE and R-squared. Among the models, the Random Forest model provided the most accurate predictions, but all models offer valuable insights into how lifestyle factors affect BMI.

Visualizations and model outputs are included to better communicate the findings and highlight the importance of machine learning in making data-driven predictions about BMI levels. 

The dataset includes records from individuals in Mexico, Peru, and Colombia, with features such as age, weight, calorie consumption, physical activity, and more. The project shows the power of machine learning in understanding public health challenges like obesity and provides actionable insights for managing weight.

**Link to dataset**: [Kaggle - Obesity Levels Dataset](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels/data)


# Save the updated content to a markdown file
file_path_ml_md = '/mnt/data/README_BMI_Obesity_Project_ML.md'

with open(file_path_ml_md, 'w') as file:
    file.write(content_ml)

file_path_ml_md
