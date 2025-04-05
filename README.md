# Car Price Prediction using Linear Regression
This project explores a dataset of used cars to build a machine learning model that predicts car prices based on various features like year of registration, brand, fuel type, and more.


## Project Objectives

- Clean and preprocess real-world car data
- Handle missing values and outliers
- Apply one-hot encoding to categorical variables
- Build a Linear Regression model to predict car prices
- Evaluate the model using R² Score and Mean Squared Error
- Visualize insights using Seaborn and Matplotlib

## 🔍 Key Steps

1. **Data Cleaning**
   - Dropped irrelevant or high-cardinality columns (`name`, `postalCode`, etc.)
   - Filtered unrealistic `yearOfRegistration` values (e.g., <1950 or >2018)

2. **Preprocessing**
   - Converted categorical features using one-hot encoding
   - Removed duplicate rows

3. **Exploratory Data Analysis**
   - Visualized price trends using `regplot`

4. **Model Building**
   - Used `LinearRegression` from scikit-learn
   - Split data into training and test sets

5. **Model Evaluation**
   - Evaluated with `R² score` and `Mean Squared Error`
   - Plotted Actual vs Predicted Prices


