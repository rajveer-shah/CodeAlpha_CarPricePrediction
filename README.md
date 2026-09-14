# Car Price Prediction using Machine Learning

This project was completed as part of the **CodeAlpha Data Science Internship**.

## Project Description

The Car Price Prediction project uses Machine Learning to predict the selling price of a used car based on various features such as car model, manufacturing year, present price, kilometers driven, fuel type, selling type, transmission, and previous owners.

The project includes data preprocessing, exploratory data analysis, feature selection, model training, and price prediction using Machine Learning algorithms.

## Dataset Features

The dataset contains the following features:

- **Car_Name** – Name or model of the car
- **Year** – Manufacturing year of the car
- **Selling_Price** – Selling price of the car and the target variable
- **Present_Price** – Current/ex-showroom price of the car
- **Driven_kms** – Total kilometers driven by the car
- **Fuel_Type** – Type of fuel used by the car
- **Selling_type** – Type of seller, such as Dealer or Individual
- **Transmission** – Type of transmission, such as Manual or Automatic
- **Owner** – Number of previous owners

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
