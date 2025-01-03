# Rossman Pharmaceuticals

## Description
This project is designed to provide utilities for data manipulation and analysis using Python. It primarily focuses on reading CSV files and processing the data for further analysis.

## Task 1 - Exploration of Customer Purchasing Behavior
Exploratory data analysis (EDA) is crucial for understanding the nature of the data and informing modeling strategies. In this task, we will explore customer behavior across various stores, focusing on how promotions and new store openings affect purchasing behavior.

### Objectives:
- Clean the data by building pipelines to detect and handle outliers and missing values.
- Visualize features and interactions to communicate findings effectively.
- Analyze the following questions:
  - Are promotions distributed similarly between training and test sets?
  - How do sales behaviors change before, during, and after holidays?
  - What seasonal purchase behaviors can be identified?
  - What is the correlation between sales and the number of customers?
  - How do promotions affect sales and customer attraction?
  - Which stores should receive promotions for maximum effectiveness?
  - How do store opening and closing times influence customer behavior?
  - What impact does the distance to competitors have on sales?
  - How do new competitors affect existing stores?

### Deliverables:
- An exploratory analysis notebook that answers all questions with appropriate plots and summary tables.

## Task 2 - Prediction of Store Sales
The goal of this task is to predict daily sales in various stores up to six weeks in advance, aiding in effective planning.

### Steps:
1. **Preprocessing**: Convert non-numeric columns to numeric, handle NaN values, and generate new features from existing data.
2. **Model Building**: Use tree-based algorithms like Random Forest Regressor within sklearn pipelines for modular and reproducible modeling.
3. **Loss Function**: Choose and justify a suitable loss function for the regression problem.
4. **Post Prediction Analysis**: Explore feature importance and estimate confidence intervals for predictions.
5. **Model Serialization**: Save models with timestamps for tracking predictions.
6. **Deep Learning Model**: Build a Long Short Term Memory (LSTM) model for time series predictions using TensorFlow or PyTorch.

## Task 3 - Model Serving API Call
Create a REST API to serve the trained machine-learning models for real-time predictions.

### Framework Selection:
- Choose a suitable framework (e.g., Flask, FastAPI, Django REST framework).

### Implementation Steps:
1. Load the serialized model from Task 2.
2. Define API endpoints to accept input data and return predictions.
3. Implement logic to preprocess input data and make predictions.
4. Format and return predictions as a response.
5. Deploy the API to a web server or cloud platform.

## Installation
To get started with this project, ensure you have Python installed on your machine. You can install the required packages using pip:

