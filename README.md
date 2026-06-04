# Car Price Prediction Using Machine Learning

## Project Overview

Car prices depend on several factors such as brand, fuel type, transmission type, present price, kilometers driven, ownership history, and vehicle age. This project uses Machine Learning techniques to predict the selling price of a car based on these features.

The objective is to build a predictive model that can estimate the market value of a used car accurately.

---

## Problem Statement

The price of a car depends on many factors, including:

* Brand value
* Fuel type
* Transmission type
* Vehicle age
* Kilometers driven
* Ownership history

This project analyzes car data and develops a machine learning model to predict car prices using these features.

---

## Dataset

Dataset Source: Car Price Prediction Dataset

The dataset contains information such as:

* Car Name
* Year
* Selling Price
* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Collection

* Load dataset from CSV or ZIP file.

### 2. Data Preprocessing

* Handle missing values.
* Remove unnecessary spaces.
* Convert categorical variables into numerical format.

### 3. Exploratory Data Analysis (EDA)

* Dataset overview.
* Correlation analysis.
* Feature distribution visualization.

### 4. Feature Engineering

* Calculate car age from manufacturing year.
* Prepare features for model training.

### 5. Model Building

* Split data into training and testing sets.
* Train Linear Regression model.

### 6. Model Evaluation

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 7. Prediction

* Predict car prices using test data.
* Compare actual and predicted values.

---

## Results

The machine learning model successfully predicts car prices based on vehicle features.

Key observations:

* Car age significantly affects resale value.
* Fuel type influences market price.
* Transmission type impacts selling price.
* Brand and vehicle condition play important roles.

---

## Project Structure

KamilGol_Task3/

├── Car_Price_Prediction.ipynb

├── README.md

├── requirements.txt

├── car_data.csv

└── screenshots/

---

## Installation

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

---

## How to Run

1. Open Google Colab or Jupyter Notebook.
2. Upload the notebook file.
3. Upload the dataset (CSV or ZIP).
4. Run all cells.
5. View model performance and predictions.

---

## Future Improvements

* Random Forest Regressor
* XGBoost Regressor
* Hyperparameter Tuning
* Model Deployment using Streamlit or Flask

---

## Author

Kamil Gol

Machine Learning Project – Car Price Prediction
