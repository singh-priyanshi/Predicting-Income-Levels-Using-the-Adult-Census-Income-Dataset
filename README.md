# Predicting Income Levels Using the Adult Census Income Dataset

This project leverages the UCI Adult Census Income dataset to predict whether an individual's income exceeds $50,000 per year based on various demographic and socioeconomic features. The project follows a structured machine learning pipeline, including data preprocessing, exploratory analysis, feature engineering, model training, and evaluation, ultimately selecting the best-performing model.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
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

## Project Structure

The project is organized as follows:

