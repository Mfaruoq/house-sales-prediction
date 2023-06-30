# house-sales-prediction
# Keras Regression Code Along Project

This project is a code along project for performing regression using Keras. It demonstrates how to apply regression techniques on a realistic dataset and focuses on feature engineering and data cleaning.

## The Data

The project uses a dataset from Kaggle, which can be found at the following link: [Kaggle House Sales Prediction Dataset](https://www.kaggle.com/harlfoxem/housesalesprediction).

The dataset contains the following feature columns:

- id: Unique ID for each home sold
- date: Date of the home sale
- price: Price of each home sold
- bedrooms: Number of bedrooms
- bathrooms: Number of bathrooms, where .5 accounts for a room with a toilet but no shower
- sqft_living: Square footage of the apartments' interior living space
- sqft_lot: Square footage of the land space
- floors: Number of floors
- waterfront: A dummy variable for whether the apartment was overlooking the waterfront or not
- view: An index from 0 to 4 of how good the view of the property was
- condition: An index from 1 to 5 on the condition of the apartment
- grade: An index from 1 to 13 indicating the quality of construction and design
- sqft_above: The square footage of the interior housing space that is above ground level
- sqft_basement: The square footage of the interior housing space that is below ground level
- yr_built: The year the house was initially built
- yr_renovated: The year of the house’s last renovation
- zipcode: The zipcode area the house is located in
- lat: Latitude
- long: Longitude
- sqft_living15: The square footage of interior housing living space for the nearest 15 neighbors
- sqft_lot15: The square footage of the land lots of the nearest 15 neighbors

## Usage

To run the code, follow these steps:

1. Install the necessary dependencies: pandas, numpy, matplotlib, seaborn, sklearn, and tensorflow.
2. Download the dataset from the provided Kaggle link and save it as 'kc_house_data.csv' in the appropriate location.
3. Open the Jupyter Notebook or Python script containing the code.
4. Run the code cells or execute the script.

The code performs exploratory data analysis, feature engineering, data preprocessing, model creation, training, and evaluation.

## Contributing

Contributions to the project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

