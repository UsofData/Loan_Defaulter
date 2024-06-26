# Loan_Defaulter

## Table of Contents
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Project Description
This project aims to predict loan defaults using machine learning techniques. It includes extensive Exploratory Data Analysis (EDA), data cleaning, and classification models.

## Dataset
The dataset for this project is sourced from the following Kaggle competition:

[Kaggle: Loan Defaulter Dataset](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter?select=previous_application.csv)

The dataset contains information about previous loan applications and their outcomes, which is used to train the model to predict future defaults.

## Installation
To run this project, you need to have Python installed along with the required libraries. You can install the necessary libraries using:

```sh
pip install -r requirements.txt
```

## Usage
The project consists of the following main files:

Loans.ipynb: The Jupyter notebook containing all the code and analysis.
Loans Defaulter (Summary).pptx: A PowerPoint presentation summarizing the findings.

To run the notebook, navigate to the project directory and start Jupyter Notebook:

```sh
jupyter notebook Loans.ipynb
```

## Results
After performing the analysis and classification, the model achieved the following results:

Random Forest Accuracy: 95.54%
ROC AUC Score: 0.9554
The classification report and confusion matrix indicate a significant improvement in detecting loan defaults after handling class imbalance with SMOTE.