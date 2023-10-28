# Predict Used Car Prices
Data cleaning, visualization, and modeling on 3 millions real world used car details for predicting prices. The modeling notebook demonstrates how to use Autogluon to find out best models for this tabular data and then predict the price using several regression models. The CatBoost regressor gave the best prediction on the test data.

## Data
The data is available for download on Kaggle https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset/

## Setup
1. Download the repo
2. Download the data `used_cars_data.csv` (9.9 GB) to the directory of the repo
3. Install the requirements `requirements.txt`
4. Run the notebook `cleaning_car_data-release.ipynb` to clean the data and generate cleaned data `used_cars_cleaned.csv`
5. Run the notebook `used_car_modeling_release.ipynb`
