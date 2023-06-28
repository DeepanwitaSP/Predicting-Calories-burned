# Predicting Calories burned

This project aims to predict the number of calories burned by a user based on their exercise and personal information.
It utilizes a machine learning algorithm called the XGBoost regressor, to make predictions.

## Data sets

The project uses two datasets:
exercise.csv: This dataset contains exercise-related information such as age, height, weight, and duration of exercise for each user, etc.
calories.csv: This dataset contains the target variable, which is the actual number of calories burned by each user.

## Data preprocessing:

Before training the model, some data preprocessing steps are performed:
Merging datasets: Both datasets are merged based on the 'User_ID' column.
Replacing gender labels: The gender labels 'male' and 'female' are replaced with numeric values '0' for male and '1' for female to make them suitable for the model.

## Libraries used

numpy: For mathematical computing in Python.
pandas: For data manipulation and analysis.
matplotlib.pyplot: library for creating visualizations.
seaborn: A statistical data visualization library based on matplotlib.
sklearn.model_selection: A module in scikit-learn for model selection and evaluation.
sklearn.preprocessing: A module in scikit-learn for data preprocessing tasks.
sklearn.metrics: A module in scikit-learn for evaluating model performance.
xgboost: A gradient boosting library for machine learning.

## Conclusion

The model is trained on the training set and evaluated on both the training and validation sets. 
The mean absolute error (MAE) is used as the evaluation metric to measure the prediction error.
The trained model's performance on the training and validation sets is printed, showing the MAE for each set.

