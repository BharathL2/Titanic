# Titanic Survival Prediction

This project predicts the survival of passengers aboard the Titanic using machine learning. The dataset comes from the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic).

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Results](#models-and-results)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

The goal of this project is to predict whether a passenger survived the Titanic disaster (binary classification). Using the given dataset, we perform data preprocessing, exploratory data analysis (EDA), and train machine learning models like Logistic Regression and Random Forest.

---

## Dataset Description

The dataset consists of the following files:
- **train.csv**: Contains features and survival labels for training the model.
- **test.csv**: Contains features to predict survival outcomes.
- **gender_submission.csv**: Sample submission file from Kaggle.

Key features include:
- `Pclass`: Ticket class (1, 2, or 3).
- `Sex`: Gender of the passenger.
- `Age`: Age of the passenger.
- `Fare`: Ticket fare.
- `Embarked`: Port of embarkation.

---

## Project Structure



Titanic-Survival-Prediction/ ├── data/ │ ├── train.csv │ ├── test.csv ├── notebooks/ │ ├── analysis.ipynb ├── src/ │ ├── model.py ├── submission.csv ├── README.md ├── requirements.txt └── .gitignore

---



## Models and Results

### Models Used:
- Logistic Regression
- Random Forest Classifier

Logistic Regression
Random Forest Classifier



### Key Metrics:

| Metric      | Logistic Regression | Random Forest |
|-------------|----------------------|---------------|
| Accuracy    | 80%                 | 85%           |
| F1-Score    | 78%                 | 83%           |

The Random Forest model outperformed Logistic Regression with better accuracy and robustness.

---


Contributing
If you’d like to contribute, feel free to fork this repository and create a pull request. Any improvements or suggestions are welcome!
---

### Key Points for Your Project
- Modify the metrics and models based on your actual results.
- Include any unique insights or features you've added (e.g., custom feature engineering).
- If your code is structured differently, update the project structure section accordingly.

Let me know if you’d like help customizing this template further!
