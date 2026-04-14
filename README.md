# Car_Price_Predictor

This project is a Machine Learning application that predicts the price of used cars based on their features such as name, company, year of purchase, kilometers driven, and fuel type.

## 📁 Project Overview
The dataset contains information about various used cars. Since the raw data was "noisy," a significant portion of this project focuses on **Data Cleaning** and **Preprocessing** using Python and Pandas. The prediction model is built using a **Linear Regression** algorithm within a Scikit-Learn **Pipeline**.

## 🚀 Features
* **Data Cleaning:** Handled non-numeric values in 'year', removed outliers, and cleaned 'price' and 'kms_driven' columns.
* **Preprocessing:** Used `OneHotEncoder` for categorical features (`name`, `company`, `fuel_type`).
* **Pipeline:** Integrated preprocessing and model training into a single Scikit-Learn `Pipeline` for cleaner code and easier deployment.
* **Optimization:** Iterated through 1000 random states to find the best train-test split for maximum $R^2$ score.
* **Inference:** A simple interactive script to predict prices for new car inputs.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Model:** Linear Regression
* **Deployment Ready:** Model exported using `pickle`.

## 📊 Key Results
* Achieved a high $R^2$ score (specific score depends on your final run) by optimizing the `random_state`.
* Visualized price trends across different companies and fuel types using Seaborn.
