# **House Price Prediction For Boston vs Seattle for Airbnb**
![5ea352e7f5d12a296913bc52_1_AkY4Z8IN-byq7ecW9YHTIw](https://github.com/user-attachments/assets/143dc4a5-6005-4d40-9277-ef3b3c476cf1)

My medium post : https://medium.com/@nadaayoussef.202/unlocking-the-secrets-of-airbnb-pricing-in-boston-and-seattle-a-data-science-journey-ad03a178a15c
## Overview

This project aims to predict the prices of Airbnb listings in Boston and Seattle using various machine learning models. The project is part of the Udacity Data Science Nanodegree program.

## Table of Contents

- [Motivation](#motivation)
- [Libraries Used](#libraries-used)
- [Files in the Repository](#files-in-the-repository)
- [Techniques and Algorithms](#techniques-and-algorithms)
- [Modeling](#modeling)
- [Results](#results)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Motivation

The goal of this project is to analyze and predict the prices of Airbnb listings in Boston and Seattle. By understanding the factors that influence pricing, we can provide insights for hosts to optimize their listings and for guests to find better deals.

## Libraries Used

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Files in the Repository

- `data/`: Contains the datasets used for the project.
  - `seattle.csv`: Seattle Airbnb data.
  - `boston.csv`: Boston Airbnb data.
- `notebooks/`: Jupyter notebooks for data exploration and model building.
    - Udacity_BS_project.ipynb
- `README.md`: This file, providing an overview of the project.

## Techniques and Algorithms

### Techniques Used

1. **Data Cleaning**: This involved handling missing values, outliers, and ensuring correct data types. Cleaning the data was crucial to ensure the accuracy of the models.
2. **Exploratory Data Analysis (EDA)**: EDA helped in understanding the distribution of data and relationships between features. Visualizations were used to identify trends and patterns.
3. **Feature Engineering**: New features were created to improve model performance. For example, features like the number of reviews, availability, and location-specific attributes were engineered.

### Algorithms Used

1. **Linear Regression**: Used for its simplicity and interpretability. It helped in understanding the linear relationship between features and the target variable.
2. **Decision Trees**: Provided a non-linear approach to model the data. They were useful in capturing complex interactions between features.
3. **Random Forest**: An ensemble method that improved the model's accuracy by reducing overfitting. It combined multiple decision trees to provide a more robust prediction.

### Previous Mistakes and Notes

1. **Overfitting with Complex Models**: Initially, complex models like Random Forest were overfitting the training data. This was mitigated by tuning hyperparameters and using cross-validation.
2. **Ignoring Feature Scaling**: Some models performed poorly because feature scaling was ignored. Implementing standardization improved model performance.
3. **Feature Selection**: Including too many irrelevant features initially led to poor model performance. Feature selection techniques were applied to retain only the most significant features.

## Modeling

The project involves the following steps:

1. **Data Cleaning**: Handling missing values, outliers, and data types.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of data and relationships between features.
3. **Feature Engineering**: Creating new features to improve model performance.
4. **Model Building**: Training various machine learning models such as Linear Regression, Decision Trees, and Random Forest.
5. **Model Evaluation**: Evaluating model performance using metrics like RMSE and R².

## Results

The models were evaluated based on their performance on the test set. The best model achieved an RMSE of X and an R² of Y, indicating that it can reasonably predict the prices of Airbnb listings in both cities.

## Acknowledgements

- The datasets used in this project are sourced from Kaggle:
  - [Seattle Airbnb Data](https://www.kaggle.com/datasets/airbnb/seattle/data)
  - [Boston Airbnb Data](https://www.kaggle.com/datasets/airbnb/boston/code)
- Both datasets are licensed under the [Creative Commons Public Domain License (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/).
- This project is part of the Udacity Data Science Nanodegree program.

## License

This project is licensed under the [Creative Commons Public Domain License (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/).
