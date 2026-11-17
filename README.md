# Experiment - Logistic Regression (Pass/Fail Prediction)

## Aim

To implement Logistic Regression for predicting student Pass/Fail results using Python and Scikit-learn.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- Logistic Regression

## Dataset

Pass-Fail Dataset (`Pass-Fail Data.csv`)

The dataset contains the following columns:
- Student ID
- Attendance Percentage
- Homework Percentage
- Midterm Score
- Study Hours Per Week
- Pass (Target Variable)

## Procedure
1. Import the required Python libraries.
2. Load the Pass-Fail dataset using Pandas.
3. Display the first five records of the dataset.
4. Select independent variables (X):
   - Attendance Percentage
   - Homework Percentage
   - Midterm Score
   - Study Hours Per Week
5. Select the dependent variable (y) as Pass.
6. Split the dataset into training and testing sets (80:20).
7. Create a Logistic Regression model.
8. Train the model using training data.
9. Predict student Pass/Fail results using testing data.
10. Compare actual and predicted values.
11. Calculate the model accuracy.
12. Create a scatter plot between Attendance Percentage and Midterm Score.

## Result

The Logistic Regression model was successfully implemented to predict student Pass/Fail results.

The following results were obtained:
- Training and testing data split: 80:20.
- Actual test records: 20.
- Predicted values matched the actual values.
- Accuracy: 100%.

The scatter plot of Attendance Percentage
