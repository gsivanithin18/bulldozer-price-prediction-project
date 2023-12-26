# Bulldozer Price Prediction Project

## Overview

This project focuses on predicting the prices of bulldozers using machine learning techniques. The goal is to develop a model that accurately predicts the price of a bulldozer based on various features such as its age, usage, and specifications.

## Table of Contents

- [Data](#data)
- [Installation](#installation)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)

## Data

The dataset used for this project is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data. The data includes various features such as bulldozer type, age, and usage hours.

## Installation

To run the project, you need to install the required dependencies. Run the following command:

```bash
pip install -r requirements.txt
```

## Model Training

The machine learning model for predicting bulldozer prices is based on the RandomForestRegressor algorithm. The following steps outline the model training process, including hyperparameter tuning:

### 1. RandomForestRegressor Model

The initial model is built using the RandomForestRegressor from the scikit-learn library. The model is trained on the preprocessed data to learn the underlying patterns and relationships within the bulldozer features.

### 2. Hyperparameter Tuning with RandomizedSearchCV

To optimize the model's performance, hyperparameter tuning is performed using RandomizedSearchCV. This process explores a range of hyperparameter combinations to find the best configuration. The hyperparameter-tuned model is then saved for later use in making predictions.

## Results

The performance and results of the bulldozer price prediction model are summarized below:

### Model Evaluation Metrics

After training and fine-tuning the RandomForestRegressor model, the following evaluation metrics were computed on the test dataset:

- **Mean Absolute Error (MAE):**
  - Example result: MAE = 6633.7143
- **Root Mean Squared Logarithmic Error (RMSLE):**
  - Example result: MSE = 0.2967
- **R-squared (R2):**
  - Example result: R2 = 0.8071

These metrics provide insights into the accuracy, precision, and overall goodness of fit of the model. Lower MAE and RMSLE values indicate better predictive performance, while a higher R2 score signifies a stronger correlation with the actual bulldozer prices.

## Contributing

Contributions to enhance the bulldozer price prediction project are welcome! If you'd like to contribute to the bulldozer price prediction project:

1. **Fork** the repository.
2. **Clone** your forked repository to your local machine.
3. Create a new branch for your contribution: `git checkout -b feature/new-feature`.
4. Make changes and commit: `git commit -am 'Add new feature'`.
5. Push changes to your branch: `git push origin feature/new-feature`.
6. Open a **Pull Request** to the original repository.
7. Your contribution will be reviewed and merged.

Thank you for contributing!
