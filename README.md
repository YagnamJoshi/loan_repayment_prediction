# Loan Repayment Prediction

This project aims to predict whether customers of a Microfinance Institution (MFI) will repay their loans within 5 days. The prediction model uses data provided by a Telecom Industry, focusing on customer behavior and other relevant features.

## Project Overview

Microfinance Institutions (MFIs) provide small loans to individuals who do not have access to traditional banking services. Predicting loan repayment behavior is crucial for MFIs to manage risk and ensure financial sustainability. By leveraging data science and machine learning techniques, this project aims to build a robust model to predict loan repayment probabilities.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/loan-repayment-prediction.git
cd loan-repayment-prediction
pip install -r requirements.txt
Dataset
The dataset used in this project is obtained from the Telecom Industry, containing features such as customer behavior, demographic information, and loan details. The dataset is not included in this repository due to privacy concerns.

## Feature Engineering
Feature engineering plays a critical role in this project. Key steps include:

Handling missing values
Encoding categorical variables
Scaling numerical features
Creating new features from existing ones
## Model Training
Several machine learning models were evaluated to find the best-performing model. The process includes:

Splitting the data into training and testing sets
Training various models (e.g., Logistic Regression, Decision Trees, Random Forest, Gradient Boosting)
Hyperparameter tuning using Grid Search and Random Search
## Evaluation
The models were evaluated using metrics such as:

Accuracy
Precision
Recall
F1 Score
Log Loss

## Results
The final model achieved the following performance metrics:

Accuracy: 85%
Precision: 80%
Recall: 78%
F1 Score: 79%
Log Loss: 0.45

## Usage
To use the model for predictions, run the following script:
python predict.py --input data/new_customers.csv --output predictions.csv

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
