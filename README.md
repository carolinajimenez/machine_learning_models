# Machine Learning Models

This repository comprises the development of three models: the first is an unsupervised model, the second is a forecasting model and the third is a classification model.

## NSF Research Awards Abstracts Classification

This project is a Natural Language Processing (NLP) application that classifies NSF research award abstracts into categories using unsupervised clustering techniques.

### Description

The project consists of the following parts:

- Data Download: Abstracts are automatically downloaded from the NSF website in XML format and stored in a local directory.

- Data Processing: Abstracts are parsed and undergo text cleaning to remove HTML tags and other unwanted characters.

- Feature Extraction: A TF-IDF vector representation of the award abstracts is created for further clustering.

- Clustering: Abstracts are grouped into categories using the K-Means algorithm.

## Transaction Forecasting

This project aims to predict future transactional behaviors, such as the next purchase amount, based on historical transaction data.

### Overview

The project involves preprocessing transaction data, training a forecasting model using a RandomForestRegressor, and visualizing the results to interpret the model's performance.

### Features

- **Data Preprocessing**: Handles missing values, encodes categorical variables, normalizes numerical variables, and extracts features from dates.
- **Model Training**: Uses a RandomForestRegressor to predict the transaction amount based on the processed features.
- **Results Visualization**: Provides visual insights into the model's predictions, feature importances, and residuals.

## Diabetes Readmission Prediction

This project aims to predict the readmission of diabetes patients using a Support Vector Machine (SVM) model.

### Description

The dataset used contains information about diabetes patients and their hospital readmissions. The goal is to predict whether a patient will be readmitted to a hospital within 30 days, after 30 days, or not be readmitted at all.

### Project Structure

1. **Data Preprocessing**: Cleaning and transforming the data for further use in the model.
2. **Dimensionality Reduction**: Using PCA to reduce the dimensionality of the data.
3. **Model Training**: Training an SVM model to predict patient readmissions.

## Getting Started

### Prerequisites

Ensure you have Python 3.9 installed along with the packages listed in `requirements.txt`.
