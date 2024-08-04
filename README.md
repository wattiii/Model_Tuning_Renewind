# Model_Tuning_Renewind

This project demonstrates Random Forest, GBM, Ada Boots, XG Boost, and Decision Tree tuning. Data has 40 predictors, 40000 observations in the training set and 10000 in the test set. The objective is to build various classification models, tune them and find the best one that will help identify failures. 


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project demonstrates Random Forest, GBM, Ada Boots, XG Boost, and Decision Tree tuning.

## Features

- Random Forest, GBM, Ada Boots, XG Boost, and Decision Tree tuning.
- Highlight any unique or significant aspects.

## Installation

### Prerequisites

List of prerequisites or dependencies:
+ pandas
+ numpy
+ matplotlib
+ seaborn
+ scikit-learn
+ xgboost
+ imbalanced-learn

### Instructions

Provide step-by-step instructions to install and set up the project. Include code snippets where necessary.

```bash
# Clone the repository
git clone https://github.com/your-username/{{ cookiecutter.project_name }}.git

# Navigate into the project directory
cd {{ cookiecutter.project_name }}

# Install dependencies
pip install -r requirements.txt

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Run the application (Note: This script [.ipynb] still requires conversion to a .pyc file)
python3 -m Renewind_notebook
