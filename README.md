# Loan Eligibility Prediction

## Introduction
This project aims to predict the eligibility of loan applicants using machine learning algorithms. The dataset used contains various features related to the applicant's personal, financial, and loan details. Several preprocessing steps are performed, and multiple classification models are trained to determine the best-performing algorithm.

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Dependencies](#dependencies)
6. [Configuration](#configuration)
7. [Documentation](#documentation)
8. [Examples](#examples)
9. [Troubleshooting](#troubleshooting)
10. [Contributors](#contributors)
11. [License](#license)

## Installation
To run this project, you need to have Anaconda installed. Follow the steps below to set up the environment:

1. **Download the project files:**
   - Download the `Loan Eligibility.ipynb` notebook file.
   - Download the `Dataset.csv` file.

2. **Create and activate a new environment:**
   Open the Anaconda Prompt and create a new environment (e.g., `loan-env`):
   ```bash
   conda create -n loan-env python=3.8
   conda activate loan-env

## Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Loan\ Eligibility.ipynb
    ```
2. Run the cells in the notebook to preprocess the data, train the models, and evaluate their performance.

## Features
- Data cleaning and preprocessing.
- Data visualization for understanding distributions and relationships.
- Multiple machine learning models:
  - Random Forest
  - Naive Bayes
  - Decision Tree
  - K-Nearest Neighbors (KNN)
- Model evaluation and comparison.

## Dependencies
The following libraries are required to run this project:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

These dependencies can be installed via `pip` as mentioned in the installation section.

## Configuration
No additional configuration is necessary. Ensure that the `Dataset.csv` file is in the same directory as the notebook.

## Documentation
For detailed documentation, refer to the inline comments and markdown cells within the Jupyter Notebook.

## Examples
Example usage can be seen within the Jupyter Notebook. Follow the steps to load the data, preprocess it, and run the machine learning models.

## Troubleshooting
If you encounter any issues, ensure that all dependencies are installed correctly and that the dataset file is in the correct location. For further assistance, refer to the official documentation of the libraries used.

## Contributors
- **Krish Patel** - [GitHub Profile](https://github.com/yourprofile)

## License
This project is licensed under the MIT License.
