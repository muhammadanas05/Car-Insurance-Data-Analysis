# Car Insurance Data Analysis

This repository contains a Python script for analyzing car insurance data to identify the most predictive feature for insurance outcomes. The script uses logistic regression to evaluate the accuracy of different features in predicting insurance outcomes.

## Requirements

- Python 3.x
- Pandas
- Numpy
- Statsmodels

You can install the required packages using pip:

```bash
pip install pandas numpy statsmodels
```

## Data

The script uses a dataset named `car_insurance.csv`. Ensure this file is available in the same directory as the script.

## Analysis Overview

1. ### Data Preparation
   - Loads the car insurance data from the CSV file.
   - Drops the `id` column from the dataset as it is not needed for analysis.

2. ### Feature Evaluation
   - Iterates through each feature (excluding the `outcome` column) to evaluate its predictive power.
   - Uses logistic regression to model the relationship between each feature and the `outcome`.
   - Calculates the accuracy of each feature in predicting the `outcome`.

3. ### Best Feature Identification
   - Identifies and prints the feature with the highest accuracy in predicting insurance outcomes.

## Results

The script outputs a DataFrame containing:
- The feature with the highest accuracy.
- The accuracy value of this feature in predicting the insurance outcome.



Feel free to adjust the content based on your preferences or any additional details you want to include!
