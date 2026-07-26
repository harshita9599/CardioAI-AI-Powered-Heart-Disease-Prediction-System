# Methodology

The project follows a standard machine learning workflow for predicting heart disease risk.

## Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Selection
4. Model Training
5. Model Evaluation
6. Prediction Generation
7. Result Visualization

## Steps

### Data Collection

Clinical patient records containing medical parameters are collected from a heart disease dataset.

### Data Preprocessing

The dataset is cleaned by handling missing values and preparing the data for training.

### Feature Selection

Relevant medical parameters such as age, blood pressure, cholesterol, chest pain type, ECG results, and maximum heart rate are selected as input features.

### Model Training

Multiple machine learning algorithms are trained using the prepared dataset.

### Model Evaluation

The trained models are evaluated to determine their prediction performance.

### Prediction

The best-performing model is used by the Flask application to predict whether a patient is at risk of heart disease.

### Result

The prediction result is displayed to the user along with health recommendations and stored in the prediction history.
