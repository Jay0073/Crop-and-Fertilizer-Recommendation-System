# Crop and Fertilizer Recommendation System

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Building](#model-building)
- [Data Analysis](#data-analysis)
- [Contributing](#contributing)

## Project Overview
This project is a Crop and Fertilizer Recommendation System that predicts suitable crops and necessary fertilizers based on various input parameters such as nitrogen, potassium, phosphorus, temperature, and humidity. The goal is to assist farmers in making informed decisions to optimize their agricultural practices.

## Features
- Predicts suitable crops based on input soil nutrients and environmental conditions.
- Recommends fertilizers that enhance soil nutrients for the selected crop.
- Utilizes machine learning models for crop and fertilizer recommendations.
- Includes data analysis notebooks for exploring and visualizing dataset features.

## Dataset
The dataset used for this project includes:
- Soil nutrient levels (Nitrogen, Potassium, Phosphorus)
- Environmental conditions (Temperature, Humidity)
- Output recommendations for suitable crops and fertilizers.

Data analysis and processing methods are documented in the Jupyter notebooks provided.

## Installation
To run this project, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System.git
    ```

2. Navigate into the project directory:
    ```bash
    cd Crop-and-Fertilizer-Recommendation-System
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Model Building
The models for crop and fertilizer recommendations are built using the following algorithms:
 - CatBoost for Crop Recommendation
 - Decision Tree Classifier for Fertilizer Recommendation
Notebooks for model building are provided in the repository:
 - [Crop Model Building](https://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System/blob/main/crop-model-building.ipynb)
 - [Fertilizer Model Building](https://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System/blob/main/fertilizer-model-builing.ipynb)

## Data Analysis
Data analsis is conducted to explore the relationships between input features and output recommendations. The relevant notebooks are:
 - [Crop Dataset Analysis](https://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System/blob/main/cropData-analysis.ipynb)
 - [Fertilizer Dataset Analysis.ipynb](https://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System/blob/main/fertilizerData-analysis.ipynb)

## Fertilizer Predictor
This notebook provides code for user to predict the fertilizer with different parameters.
 - [Fertilizer Predictor](http://github.com/Jay0073/Crop-and-Fertilizer-Recommendation-System/blob/main/fertilizer-Prediction.ipynb)

## Contribution
Contributions are welcome! If you have suggestions or improvements, please feel free to submit a pull request.
    
