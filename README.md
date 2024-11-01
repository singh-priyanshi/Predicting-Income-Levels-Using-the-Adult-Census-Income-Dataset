# Predicting Income Levels Using the Adult Census Income Dataset

This project leverages the UCI Adult Census Income dataset to predict whether an individual's income exceeds $50,000 per year based on various demographic and socioeconomic features. The project follows a structured machine learning pipeline, including data preprocessing, exploratory analysis, feature engineering, model training, and evaluation, ultimately selecting the best-performing model.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to build a predictive model that accurately classifies whether an individual's income is above or below $50,000 annually. By analyzing features such as age, education, occupation, and work hours, this project demonstrates the potential of machine learning models in demographic-based predictions.

## Dataset

The **UCI Adult Census Income dataset** is used for this project. The dataset is available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult).

### Features

The dataset contains the following features:

- Age
- Workclass
- Education
- Education-num
- Marital-status
- Occupation
- Relationship
- Race
- Sex
- Capital-gain
- Capital-loss
- Hours-per-week
- Native-country

### Target
The target variable is a binary label:
- `>50K`: Income greater than $50,000
- `<=50K`: Income less than or equal to $50,000

## Installation
Clone the repository:
bash
git clone https://github.com/singh-priyanshi/adult-census-income.git
cd adult-census-income

Install dependencies:
bash
pip install -r requirements.txt

### Usage
Open the notebook to explore the analysis and training steps:

bash
jupyter notebook notebooks/adult-census-income.ipynb
Follow the instructions within the notebook to see each step of the process. Run all cells to load data, preprocess it, perform EDA, train models, and evaluate results.

### Results
Several machine learning models are evaluated, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
The final model selection and its performance metrics are based on accuracy, precision, recall, and F1-score.

### Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request for improvements or feature requests.
