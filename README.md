# Predicting Popular Recipes

## Project Overview

The certification I recently earned required the successful completion of two timed exams and a practical component. For the practical exam, I was given a hypothetical scenario in which my manager (Head of Data Science) gave me an assignment that was requested by another business leader (Product Manager). I was provided with instructions and a dataset to analyze, and had to provide a written report including code and output. Additionally, I recorded a presentation to give a high-level overview of my analysis and findings.

This repo contains my written report (.ipynb) and the corresponding dataset (.csv) and instructions (.pdf) from the practical exam. I am sharing this as a portfolio project for the purpose of demonstrating my Python and communication skills.

## Installation and Setup

### Code and Resources Used

- **Editor**: JupyterLab 4.0.11
- **Python Version**: 3.12.3

### Python Packages Used
- Data Manipulation:
  - `pandas` 2.2.2
  - `numpy` 1.26.4
  - `scipy` 1.13.0
- Data Visualization:
  - `matplotlib` 3.8.4
  - `seaborn` 0.13.2
- Machine Learning and Statistics:
  - `scikit-learn` 1.4.2
  - `statsmodels` 0.14.2

## Data

### Project Files
- **instructions.pdf**: instructions provided by the certification organization
- **recipe_site_traffic_2212.csv**: dataset provided by the certification organization
- **kucharczyk_predicting_popular_recipes.ipynb**: my written report including code and output

### Data Exploration, Preparation, Analysis, and Results

I performed exploratory data analysis, data preparation, and binary classification using Python to predict which recipes would lead to high traffic on the website of a company that sells meal planning and ingredient delivery services. Repeated stratified k-fold cross-validation and grid search were used for model selection and hyperparameter tuning. The logistic regression model achieved an accuracy of 81% and revealed which recipe attributes are associated with high and low website traffic. The written report (.ipynb) provides all details relating to data exploration, preparation, analysis, and results.

## References

The certification organization that provided the dataset and instructions can be found in the instructions (.pdf).