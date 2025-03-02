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
    git clone https://github.com/atharva1845/HousePricePrediction.git
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
 ```
---

This script provides a full pipeline that:

- **Loads and explores the dataset:**  
  Gain insights through data summaries, basic statistics, and an overview of the dataset structure.
- **Preprocesses the data:**  
  Transform categorical features using one-hot encoding and standardize numerical features.
- **Splits the data:**  
  Divide the dataset into training and testing sets for reliable model evaluation.
- **Trains a linear regression model:**  
  Learn the relationship between the features and house prices.
- **Evaluates model performance:**  
  Utilize metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) to assess prediction accuracy.
- **Generates visualizations:**  
  Visualize actual vs. predicted prices, examine residuals, and assess feature importance.

---

## Model Training & Evaluation

The model employs a **linear regression** approach. After training, it is evaluated using several key metrics:

- **Mean Absolute Error (MAE):**  
  The average absolute difference between the predicted and actual house prices.
- **Mean Squared Error (MSE):**  
  The average of the squared differences between predictions and actual values.
- **Root Mean Squared Error (RMSE):**  
  The square root of MSE, providing error magnitude in the same units as the target.
- **R-squared Score (R²):**  
  Indicates the proportion of variance in the target variable explained by the model.

These metrics help determine the accuracy and reliability of the predictions.

---

## Visualizations

The project includes several insightful visualizations:

- **Actual vs. Predicted Prices:**  
  A scatter plot that compares predicted house prices with the actual prices, along with a reference line (ideal fit) to easily spot deviations.
- **Residuals Distribution:**  
  A histogram (with a KDE overlay) that shows the distribution of the residuals, enabling assessment of model fit and identification of any biases.
- **Feature Importance:**  
  A bar chart that displays the contribution of each feature in predicting house prices, as indicated by the model's coefficients.

---

## Future Improvements

Planned enhancements for upcoming iterations include:

- **Advanced Models:**  
  Experiment with algorithms such as Random Forests or Gradient Boosting to potentially improve predictive performance.
- **Hyperparameter Tuning:**  
  Implement Grid Search or similar techniques to optimize model parameters.
- **Cross-Validation:**  
  Integrate cross-validation methods for a more robust model evaluation.
- **Feature Engineering:**  
  Explore additional features and interaction terms to further enhance model accuracy.
- **Deployment:**  
  Package the model as a web application using frameworks like Flask or Django to make it accessible to end-users.

---

## License

This project is licensed under the **MIT License**. For more details, see the [LICENSE](LICENSE) file.

---

## Contact

For any questions, suggestions, or collaboration opportunities, please open an issue on GitHub or contact me directly at [your.email@example.com](mailto:your.email@example.com).

---

**Happy coding and happy predicting! 🚀**
