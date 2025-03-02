# House-Price-Prediction

Welcome to the **House Price Prediction** project! This repository contains a comprehensive workflow to predict housing prices using a linear regression model. The project leverages both numerical and categorical data to build a robust predictive model.

---

## Overview

In this project, we explore a housing dataset that includes features such as area, number of bedrooms, bathrooms, stories, and additional categorical variables like main road accessibility, presence of a guest room, basement, and more. Our goal is to predict the price of a house based on these features using a linear regression model. The project covers:

- Data exploration and preprocessing
- Feature engineering (including one-hot encoding for categorical data)
- Model training and evaluation
- Visualization of results and model diagnostics

---

## Features

- **Data Exploration**: Detailed summary statistics and data insights.
- **Data Preprocessing**:
  - Selection of numerical and categorical features.
  - One-hot encoding of categorical variables.
  - Standardization of numerical features.
- **Model Training**: Implementation of a linear regression model using scikit-learn.
- **Evaluation Metrics**: Calculation of Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared score.
- **Visualizations**:
  - Scatter plot for actual vs. predicted prices.
  - Residual distribution plot to evaluate model errors.
  - Bar chart for feature importance analysis.

---

## Data

The dataset used in this project includes the following features:

- **Numerical Features**:
  - `area`: Total area of the house.
  - `bedrooms`: Number of bedrooms.
  - `bathrooms`: Number of bathrooms.
  - `stories`: Number of stories in the house.
  - `parking`: Number of parking spaces.
- **Categorical Features**:
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`

All categorical features are transformed using one-hot encoding, and the numerical features are standardized for improved model performance.

---

## Installation

To run this project locally, ensure you have Python 3.7+ installed. Follow these steps to get started:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/HousePricePrediction.git
    cd HousePricePrediction
    ```

2. **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Place the dataset:**
   - Ensure the `Housing.csv` file is located in the appropriate directory or update the file path in the code accordingly.

---

## Usage

Run the main Python script to execute the entire workflow:

```bash
python house_price_prediction.py
