# Titanic Disaster Prediction

## Overview
The sinking of the Titanic is one of the most tragic maritime disasters in history. On April 15, 1912, the RMS Titanic, considered unsinkable, collided with an iceberg during its maiden voyage, leading to the loss of 1502 out of 2224 passengers and crew due to insufficient lifeboats. In this project, we aim to predict whether a passenger on the Titanic survived or not using machine learning techniques.

## Notebooks
1. **Titanic_Scratch.ipynb**: In this notebook, logistic regression is implemented from scratch without using any libraries. The aim is to predict passenger survival based on various features.
2. **Titanic_Trees.ipynb**: This notebook focuses on data preprocessing, exploring different machine learning models, and selecting the best performing one. Libraries such as NumPy, Pandas, Matplotlib, and scikit-learn are utilized. The final model achieves approximately 79% accuracy on the test dataset.

## Data
- **train.csv**: This file is used to train the machine learning models. It contains features such as passenger class, sex, age, number of siblings/spouses aboard, number of parents/children aboard, fare, and embarked port.
- **test.csv**: The test dataset against which the trained models are evaluated.

## Submissions
- **submission_scratch.csv**: Output of the test dataset using the logistic regression model implemented from scratch.
- **submission_trees.csv**: Output of the test dataset using the selected machine learning model from the Titanic_Trees notebook.

## Instructions
1. To replicate the results or explore further, refer to the respective Jupyter notebooks.
2. Ensure all dependencies are installed before running the notebooks.
3. For any questions or issues, feel free to contact at sahilgarg3112@gmail.com.
