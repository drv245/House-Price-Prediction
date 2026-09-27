# House Price Prediction

Machine Learning project predicting house prices using Linear Regression.

## What I Did
- Loaded and explored a housing dataset (545 rows, 13 features)
- Encoded categorical features (yes/no columns + one-hot encoding for furnishing status)
- Split data into training (80%) and testing (20%) sets
- Trained a Linear Regression model using Scikit-learn
- Evaluated model performance and visualized actual vs predicted prices

## Results
- **R² Score:** 0.65 — model explains 65% of price variation
- **Mean Absolute Error:** ₹9.7 lakhs

## Key Finding
Model performs well for mid-range houses but under-predicts for high-value 
properties (₹1 crore+), likely due to fewer expensive-house examples in the 
dataset and missing features like exact location or premium amenities.

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (LinearRegression, train_test_split, r2_score, mean_absolute_error)
- Matplotlib
