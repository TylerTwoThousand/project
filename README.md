## Project: Logistic Regression Analysis

This project is about using a simple machine learning model called Logistic Regression to look at a dataset with 10 different features. The main goal is to train the model to predict a "target" category and then make some plots to see how well those predictions actually match the real data.

## Folder Structure

* data/ - Contains dataset.csv
* docs/ - Meeting notes and PDF reports
* images/ - Visualizations of the data and model results
* reports/ - The main analysis notebook (Report.ipynb)
* src/ - Python scripts for data generation

## Getting Started

The environment is managed through Conda. To set this up on your own machine:

1. Create the environment using the yaml file:
conda env create -f environment.yaml
2. Activate it:
conda activate project-env
3. Open JupyterLab and make sure you select the "project-env" kernel before running the cells in Report.ipynb.

## Requirements

This project requires Python 3.10 or higher. The main libraries used are pandas for data handling, matplotlib for plotting, and scikit-learn for the machine learning pipeline (specifically LogisticRegression, train_test_split, and accuracy_score).