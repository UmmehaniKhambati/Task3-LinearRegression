# Task3-LinearRegression

Objective
To implement and understand Simple & Multiple Linear Regression using the housing price dataset and evaluate model performance using key metrics.

#Tools & Libraries
- Python  
- Scikit-learn  
- Pandas  
- Matplotlib  
- NumPy  

#Dataset
  Source:Kaggle – Housing Price Prediction Dataset

 # Columns Used:  
- price (target)
- Numerical: area, bedrooms, bathrooms, stories, parking
- Categorical (encoded): mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus

#Preprocessing Steps
- Encoded binary categorical columns (yes/no → 1/0)
- One-hot encoded 'furnishingstatus' to handle 3 categories
- Removed rows with missing values
- Defined feature matrix X and target y

# Models Implemented

#Multiple Linear Regression
- Features used: all numeric and encoded categorical features
- Target: price
- Model: LinearRegression() from sklearn


#Simple Linear Regression (area vs. price)


#Visualizations
- Actual vs Predicted Price (Multi-feature model)
- Regression Line Plot (Area vs Price)

#Learnings
- Understood and implemented both Simple and Multiple Linear Regression
- Learned to handle categorical data through encoding
- Evaluated model using key regression metrics
- Visualized how regression models fit real-world data

