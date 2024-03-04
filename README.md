# NLP_CW1

# Project Title

## Overview
This project repository contains a set of Jupyter Notebook files, data, and documentation essential for the machine learning model which predicts labels for a given dataset.



## Directory Structure



- `code/`: Contains Jupyter Notebook files detailing the model development and evaluation process.

- `processed_data/`: Includes processed datasets that have been transformed and are ready for modeling.

- `raw_data/`: Contains the original, unprocessed datasets downloaded from the provided GitHub URL.



## Code



The `code` directory includes the following Jupyter Notebook files:



- `ensemble_model_cw.ipynb`: Combines multiple machine learning models using soft voting to create an ensemble that predicts the final labels.

- `Part_1a_2c.ipynb`: Answers questions related to parts 1a and 2c of the project using data analysis and modeling.

- `Part_3a_and_3c.ipynb`: Provides solutions and analysis for parts 3a and 3c of the project.

- `Part_Further_Improvement_Data_Sampling.ipynb`: Contains strategies for further improvement and data sampling techniques.

- `pcl_classifier_model.ipynb`: A notebook that develops the PCL classifier model.

- `pcl_classifier_model_data_augmentation.ipynb`: Demonstrates data augmentation techniques used to enhance the PCL classifier model's performance.

- `pcl_classifier_model_preprocessing.ipynb`: Shows the preprocessing steps applied to the data before it is fed into the PCL classifier model.

- `pcl_data_analysis.ipynb`: Performs an exploratory data analysis on the dataset.

- `pcl_data_augmentation.ipynb`: Explores data augmentation methods to improve the model's training process.



## Data



- `processed_data/`

  - `tedf1.csv`: Transformed dataset ready for model training.

  - `trdf1.csv`: Another transformed dataset prepared for training.

  - `pcl_augmented_data.csv`: Dataset that has been augmented to enhance model performance.



- `final_data_with_cw/`

  - Contains all the base data that was downloaded from the provided GitHub URL and intermediate data files generated from model training



## Predictions



- `dev.txt`: Contains the predicted labels from our model for the test set, alongside the true labels for validation.

- `test.txt`: Includes the predicted labels for the official test set, which does not contain the true labels.

"""
