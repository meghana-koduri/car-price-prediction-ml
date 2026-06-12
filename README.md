# Car Price Prediction using Machine Learning

## Project Overview

This project predicts the selling price of used cars using Machine Learning regression models.

The objective is to estimate the resale value of a car based on important vehicle attributes such as manufacturing year, fuel type, transmission type, kilometers driven, seller type, and ownership history.

This project demonstrates data preprocessing, feature engineering, model training, evaluation, and price prediction.

---

## Problem Statement

Used car prices depend on multiple factors and vary significantly in the market.

The goal of this project is to build a machine learning model capable of predicting a car’s selling price accurately based on historical car data.

---

## Dataset Features

The dataset contains the following features:

- Present Price → Current ex-showroom price of the car
- Kms Driven → Total distance driven by the vehicle
- Fuel Type → Petrol / Diesel / CNG
- Seller Type → Dealer / Individual
- Transmission → Manual / Automatic
- Owner → Number of previous owners
- Car Age → Age of the car in years

Target Variable:

- Selling Price

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Encoding Categorical Variables  
6. Splitting Train and Test Data  
7. Model Training  
8. Model Evaluation  
9. Price Prediction  

---

## Machine Learning Models Used

- Linear Regression
- Random Forest Regressor

---

## Evaluation Metrics

The models were evaluated using:

- R² Score  
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  

---

## Example Prediction

Input:

Present Price = 6.0  
Kms Driven = 40000  
Fuel Type = Petrol  
Seller Type = Dealer  
Transmission = Manual  
Owner = 0  
Car Age = 5 Years  

Predicted Selling Price:

₹ 4.8 Lakhs (example)

---

## Project Structure

car-price-prediction-ml/

├── car_dataset.csv  
├── car_price_prediction.ipynb    
├── requirements.txt  
├── README.md  
 

---

## Future Improvements

- Improve model accuracy using XGBoost  
- Build a Streamlit web application  
- Deploy the model online  
- Add advanced feature engineering techniques  

---


## Conclusion

This project demonstrates the application of machine learning regression techniques to solve real-world price prediction problems and highlights practical skills in data preprocessing, model building, and predictive analytics.
