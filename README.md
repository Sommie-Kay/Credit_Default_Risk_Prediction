# Credit Default Risk Prediction 

## Introduction
This project focuses on predicting credit risk using machine learning techniques, particularly the LightGBM model. The project aims to develop a robust predictive model that can accurately assess the creditworthiness of individuals based on various features.

## Business Objective
The primary objective of this project is to assist financial institutions in making informed decisions regarding loan approvals by predicting the likelihood of credit default. By leveraging machine learning algorithms, the goal is to minimize the risk associated with lending while maximizing profitability.

## Details of Project
The project is structured around a model pipeline, which consists of several Python scripts organized in a folder. The key components of the project are as follows:

### Model Pipeline Folder
The Model Pipeline folder contains Python scripts for different stages of the machine learning pipeline:

- **processing.py**: Contains functions and classes for data preprocessing tasks.
- **training.py**: Trains the LightGBM model using preprocessed data.
- **utilis.py**: Houses utility functions and classes utilized throughout the pipeline.
- **engine.py**: Main script responsible for orchestrating the entire pipeline and producing the trained model.

Executing the `engine.py` script triggers the entire pipeline, resulting in the generation of the trained LightGBM model.

### LightGBM
LightGBM is a gradient boosting framework that is renowned for its speed, efficiency, and accuracy. It is particularly well-suited for large datasets and has been widely adopted in various machine learning applications, including credit risk prediction.

### Data
The project Dataset was uploaded along side all other files. The dataset contains relevant features such as demographic information, financial history, and credit risk indicators.

## Conclusion
By leveraging machine learning techniques, particularly LightGBM, this project aims to provide financial institutions with a reliable tool for assessing credit risk. The trained model can assist in automating loan approval processes, improving efficiency, and mitigating the risk of default.
