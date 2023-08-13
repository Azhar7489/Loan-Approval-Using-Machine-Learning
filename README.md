# Loan-Approval-Using-Machine-Learning
Minor Project for approving loans to customers
![Loan Approval](loan_approval_image.jpg)

## Overview

This repository contains a machine learning project focused on predicting loan approvals using a dataset of historical loan application data. The goal of this project is to develop a predictive model that can assist in automating the loan approval process, making it more efficient and accurate.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- 
## Dataset

The dataset used for this project is sourced from [XYZ Dataset Source](link_to_dataset). It includes various features such as applicant's age, income, credit score, loan amount, etc., and their corresponding loan approval status (0 for not approved, 1 for approved). The dataset is available in the `data` directory.

## Project Structure

─ data/ # Dataset files
─ notebooks/ # Jupyter notebooks for data exploration, preprocessing, and model development
─ src/ # Source code for the machine learning model
─ data_preprocessing.py
─ model_training.py─ loan_approval_app.py # Example application for using the trained model
─ requirements.txt # Python dependencies


## Installation

1. Clone this repository: `git clone https://github.com/your-username/loan-approval.git`
2. Navigate to the project directory: `cd loan-approval`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Explore the Jupyter notebooks in the `notebooks` directory to understand the data preprocessing and model development steps.
2. Use the provided scripts in the `src` directory to preprocess the data and train the model.
3. Deploy the trained model using the example application in `src/loan_approval_app.py`.

## Model

We have used a [Decision Tree](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.DecisionTreeClassifier.html) classifier for this loan approval prediction task. The model is trained on preprocessed data and is capable of predicting whether a loan application will be approved or not.

## Evaluation

The model's performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into how well the model predicts loan approvals based on the dataset.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. For major changes, please discuss them in advance.


