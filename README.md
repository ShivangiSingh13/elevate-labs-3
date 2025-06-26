# Task 3 assigned
🏡 California Housing Price Prediction with Linear Regression
This project demonstrates a simple Linear Regression model applied to the California Housing Dataset. It uses only one feature—housing_median_age—to predict the target variable, median_house_value.

✅ Objective
To understand how the age of housing correlates with house prices in California using:
Linear regression
Model evaluation metrics (MAE, MSE, R²)
Data visualization (scatter plot and regression line)

📂 Dataset
File: housing.csv
Source: California Housing Dataset
Key Columns Used:
Feature (X): housing_median_age
Target (Y): median_house_value

🧪 Workflow
Import Libraries: pandas, seaborn, matplotlib, sklearn
Data Preprocessing:
Checked for null values
Removed rows with missing data
Train-Test Split: Using train_test_split() from sklearn.model_selection
Model Fitting: Linear regression from sklearn.linear_model
Evaluation Metrics:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score (Coefficient of Determination)
Visualization:
Scatter plot of test data
Regression line overlaid for visual insight
Interpretation:
Slope and intercept used to form a regression equation
Explained how age influences housing prices

📈 Output Sample
Regression Equation:
median_house_value = slope × housing_median_age + intercept
Example: A one-unit increase in housing age leads to an approximate increase of X dollars in house value (based on slope).

🛠️ Libraries Used
bash
Copy
Edit
pandas
matplotlib
seaborn
scikit-learn

💡 Future Enhancements
Add more features like total_rooms, median_income, etc.
Use Polynomial Regression or Ridge/Lasso for better fit
Deploy model with an interactive UI
