# Favorita Store Sales Forecasting

This repository contains the code and relevant files for a sales forecasting model for Favorita stores in Ecuador. The goal of this project was to forecast sales of thousands of product families. The model considers various features including dates, store and product information, and promotional data. The project made use of a hybrid boosted model, combining Linear Regression and Random Forest algorithms, to predict the sales.

## Project Overview

- **Goal**: Forecast the sales of Favorita stores, a grocery chain located in Ecuador.
- **Data**: The dataset includes sales data of thousands of product families, dates, store and product information, promotional details, and more.
- **Model**: Implemented a hybrid boosted model integrating Linear Regression and Random Forest algorithms.
- **Performance**: The model yielded a Root Mean Squared Logarithmic Error (RMSLE) of 0.43 in sales forecasting.

## Files

- `Data`: This folder contains all relevant data files.
- `FavoritaSalesForecasting.ipynb`: This Jupyter Notebook contains all the code used in this project.
- `README.md`: The file you're currently reading.

## Model Details

The chosen model is a hybrid between Linear Regression and Random Forest, taking advantage of the strengths of both. The model first uses Linear Regression to make initial predictions, then uses a Random Forest model to learn from the residuals of the first model and adjust the final predictions. This hybrid approach improves accuracy by combining the simplicity and interpretability of linear models with the flexibility of tree-based models.

## Requirements

This project requires Python 3.x and the following Python libraries installed:

- Numpy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## How to Run

To replicate and run this project:

1. Clone this repository to your computer.
2. Install the necessary Python packages.
3. Run the Jupyter notebook.

## Results

The model successfully forecasted the sales of Favorita stores with a Root Mean Squared Logarithmic Error (RMSLE) of 0.43, demonstrating the potential of hybrid models for retail forecasting tasks.

## Contact

If you have any questions or would like to contribute, feel free to reach out. Pull requests are welcome.
