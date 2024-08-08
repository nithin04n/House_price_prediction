# House_price_prediction

# Real Estate Price Prediction

This repository contains a Python project for predicting real estate prices based on various features such as area, square footage, distance to the main road, number of bedrooms, and more. The model is trained using linear regression and other machine learning techniques to predict the sales price of properties.

## Project Structure

- `housing_data.csv`: The dataset containing the features and target variable (sales price).
- `real_estate_price_prediction.ipynb`: The Jupyter notebook containing the code for data preprocessing, exploratory data analysis, model training, and evaluation.
- `README.md`: This file providing an overview of the project.

## Dataset

The dataset contains the following features:

- `AREA`: Area where the property is located.
- `INT_SQFT`: Interior square footage of the property.
- `DIST_MAINROAD`: Distance to the main road in meters.
- `N_BEDROOM`: Number of bedrooms in the property.
- `N_BATHROOM`: Number of bathrooms in the property.
- `N_ROOM`: Total number of rooms in the property.
- `SALE_COND`: Sales condition of the property.
- `PARK_FACIL`: Whether parking facility is available (Yes/No).
- `DATE_BUILD`: Year the property was built.
- `BUILDTYPE`: Type of building (House/Commercial).
- `UTILITY_AVAIL`: Availability of utilities (AllPub/NoSewr/NoSeWa/ELO).
- `SALES_PRICE`: The target variable, indicating the sales price of the property.

## Getting Started

### Prerequisites

Make sure you have the following software installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/real-estate-price-prediction.git
   cd real-estate-price-prediction
