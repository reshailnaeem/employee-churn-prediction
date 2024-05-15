# Employee Churn Prediction

This is an employee churn prediction model that uses various features given by the HR department to predict employee churn. The dataset is Human Resource from Kaggle.

https://www.kaggle.com/datasets/colara/human-resource

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Data](#data)
- [License](#license)

## Features

- Conducted general Exploratory Data Analysis (EDA) to gain insights into the dataset
- Used a loop to check different classification algorithms to choose the best based on various metrics
- Implemented LightGBM Classifier for optimal predictive performance
- Evaluated the final model using learning curves and cross-validation to ensure robustness
- Used `shap` to get and plot the important features in the final model
- Wrapped the model in a GUI using `gradio`; please refer to the end of the notebook for details

## Installation

Use any Python >= 3.11 version along with the requirements.txt file in the repository. I used 3.12 with the latest versions of all libraries.

```bash
# Installing using repo file
pip install -r requirements.txt
```

## Data
Link to the original dataset on Kaggle:
https://www.kaggle.com/datasets/colara/human-resource

## License

Employee Churn Prediction © 2024 by Reshail Naeem is licensed under Attribution-NonCommercial-ShareAlike 4.0 International 
