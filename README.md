# Calorie Burn Prediction

This repository contains a machine learning model to predict the number of calories burned based on input features such as age, gender, height, weight, heart rate, and duration of physical activity. This project was developed during the Edify Internship program.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)

## Overview
The goal of this project is to accurately predict the calories burned during physical activities using personal metrics like age, gender, height, and heart rate. This project leverages Python libraries for data preprocessing and machine learning model building.

## Dataset
The dataset includes personal and exercise data with features like:
- Age
- Gender
- Height
- Weight
- Heart Rate
- Duration of Physical Activity

**Dataset Source:** [https://www.kaggle.com/code/muskanjha/calories-burnt-prediction/input]

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Karan27q/Edify-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Edify-project
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
Once the dependencies are installed, follow these steps:

1. **Preprocess the data:** Clean and preprocess the dataset.
2. **Train the model:** Run the following command to train the model:
    ```bash
    python train.py
    ```
3. **Make predictions:** Use the trained model to make predictions on new data:
    ```bash
    python predict.py --input new_data.csv --output predictions.csv
    ```

## Model Details
The models used include:
- **RandomForestRegressor** and **LinearRegression** for predicting continuous values.
  
The model is evaluated using performance metrics such as **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)**.

## Results
The model achieves an R-squared score of 93% on the test dataset, with detailed results on accuracy and error metrics.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements.

