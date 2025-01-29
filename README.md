<h1 align="center">House Price Prediction Project</h1>

# Overview

This project aims to predict house prices in Bengaluru, India, based on various features such as location, size, number of bedrooms (BHK), and number of bathrooms. The dataset used is processed to remove inconsistencies, perform feature engineering, and apply different regression models to find the best predictor.

# Project Highlights

- **Data Collection:** Load and inspect the dataset.

- **Data Cleaning:** Handle missing values, remove outliers, and standardize data.

- **Feature Engineering:** Create new features like 'bhk' and 'price_per_sqft'.

- **Model Selection:** Train different regression models using GridSearchCV.

- **Prediction:** Develop a function to predict house prices based on user input.

- **Evaluation:** Assess model performance using appropriate metrics.


# Dataset
The dataset used in this project can be downloaded from Kaggle. It contains information about various properties in Bengaluru, including:

`area_type`: Type of area (e.g., Super built-up, Plot, Built-up, Carpet).

`availability`: Availability status of the property.

`location`: Location of the property.

`size`: Size of the property in BHK or Bedroom.

`total_sqft`: Total square footage of the property.

`bath`: Number of bathrooms.

`balcony`: Number of balconies.

`price`: Price of the property in Lakhs.


# Future Work

- **Feature Engineering:** Explore more features that could improve model performance.

- **Model Tuning:** Experiment with different machine learning models and hyperparameter tuning.

- **Deployment:** Deploy the model as a web application for real-time predictions.

- **Data Augmentation:** Collect more data to improve the model's accuracy and robustness.


# How to Use

Clone the repository.

Install the required libraries using `pip install -r requirements.txt`.

Run the Jupyter notebook `House_price_prediction.ipynb` to see the data processing, model training, and evaluation steps.

Use the trained model to predict house prices based on user input.


# Dependencies

Python 3.x

Pandas

NumPy

Matplotlib

Scikit-learn


# Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.