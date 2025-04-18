# ELECTRIC_VEHICLE_POPULATION--CLASSIFICATION

## Overview

This project analyzes the Electric Vehicle Population Data from Data.gov to predict whether a vehicle is a Battery Electric Vehicle (BEV) or a Plug-in Hybrid Electric Vehicle (PHEV) based on various features. The dataset includes information on EVs registered in Washington State through the Department of Licensing.

## Objective

The primary goal is to develop a model that accurately classifies electric vehicles into BEV or PHEV categories using the available dataset features.

## Data Source

The dataset is sourced from [Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data).

## Data Description

The dataset includes the following features:

*   VIN (1-10): Vehicle Identification Number (first 10 characters)
*   County: County where the vehicle is registered
*   City: City where the vehicle is registered
*   State: State where the vehicle is registered (WA)
*   Postal Code: Postal code of the registration address
*   Model Year: The model year of the vehicle
*   Make: Vehicle manufacturer
*   Model: Vehicle model
*   Electric Vehicle Type: Type of electric vehicle (BEV or PHEV)
*   Clean Alternative Fuel Vehicle (CAFV) Eligibility: Eligibility for clean alternative fuel vehicle incentives
*   Electric Range: The electric range of the vehicle
*   Base MSRP: Base Manufacturer's Suggested Retail Price
*   Legislative District: Legislative district of the vehicle registration
*   DOL Vehicle ID: Department of Licensing vehicle ID
*   Vehicle Location: Geographic location of the vehicle
*   Electric Utility: Electric utility serving the vehicle location
*   2020 Census Tract: 2020 Census Tract for the vehicle location

## Methodology

1.  **Data Loading and Exploration:** Load the dataset and explore its structure and initial statistics.
2.  **Data Cleaning and Preprocessing:** Handle missing values, and convert categorical features into numerical format.
3.  **Model Training:** Train several classification models.
4.  **Model Evaluation:** Evaluate the performance of each model using accuracy, precision, recall, and F1-score.
5.  **Model Prediction:** Predict whether a vehicle is a BEV or a PHEV.

## Results

The following models were trained and evaluated:

1.  Logistic Regression
2.  Naive Bayes Classifier
3.  Random Forest Classifier
4.  Gradient Boosting Classifier
5.  Decision Tree

The Decision Tree model achieved the highest accuracy of 1.00.

## Usage

1.  Clone the repository.
2.  Install the necessary dependencies.
3.  Run the Jupyter Notebook to reproduce the analysis.

## Dependencies

*   pandas
*   scikit-learn
*   numpy

## Conclusion

The project demonstrates the use of machine learning techniques to classify electric vehicles based on their characteristics. The Decision Tree model provides a high level of accuracy in distinguishing between BEVs and PHEVs.
