NASA Airfoil Noise Prediction
This project performs data cleaning and builds a linear regression model to predict airfoil noise levels based on aerodynamic features from the NASA Airfoil Noise dataset.

Features
Data cleaning: duplicate and missing value removal

Data format conversion: CSV to Parquet

Simple ML pipeline: train/test split, linear regression training, and evaluation

Model evaluation metrics: MSE, MAE, R²

Model interpretability: coefficient inspection

Getting Started
Dataset: Place NASA_airfoil_noise_raw.csv in the DATASET folder or update the path in the script.

Run the script: Executes data preprocessing, model training, evaluation, and saves cleaned data as Parquet.

Requirements: Python 3.x, pandas, scikit-learn, pyarrow or fastparquet (for Parquet support).

Usage
python airfoil_noise_prediction.py
Results
Prints dataset info, cleaning steps, and evaluation metrics.

Outputs model coefficients for feature impact analysis.

Saves cleaned dataset as clean_airfoil_data.parquet.
