# Breast-Cancer-Detection-and-Analysis
## Overview
This project aims to detect breast cancer using machine learning techniques. It involves a comprehensive workflow starting from data exploration and preprocessing to model training and evaluation. The objective is to build an accurate model that can classify tumors as benign or malignant based on various features.

### Techniques and Methods Used
### 1. Data Import and Exploration

- **Library Imports**: Essential libraries such as `numpy`, `pandas`, `matplotlib`, and `seaborn` were imported for data manipulation and visualization.
- **Dataset Import**: The dataset was loaded from a CSV file.
- **Initial Exploration**: Various checks and summaries were performed to understand the dataset's shape, data types, and basic statistics.

### 2. Data Cleaning

- **Handling Missing Values**: Identified and handled missing values by dropping columns that were mostly empty, specifically the 'Unnamed: 32' column.
- **Categorical Data Handling**: Examined and encoded categorical columns as necessary.

### 3. Data Preprocessing

- **Normalization**: Scaled the features using standard scaling to ensure they contribute equally to the model.
- **Train-Test Split**: Split the dataset into training and testing sets to evaluate the model's performance effectively.

### 4. Model Training

- **Machine Learning Algorithms**: Applied and evaluated several machine learning algorithms, including:
  - **Logistic Regression**
  - **Random Forests**

### 5. Hyperparameter Tuning

- **Randomized Search CV**: Utilized Randomized Search Cross-Validation to find the best hyperparameters for the Random Forest model.

### 6. Model Evaluation
- **Metrics**: Evaluated the models using metrics such as accuracy, precision, recall, and F1-score.
- **Confusion Matrix**: Visualized the performance of the models with confusion matrices.
- **Cross-Validation**: Performed cross-validation to assess model stability and performance consistency.

### 7. Results and Conclusions
- **Best Model**: The Logistic Regression model with specific hyperparameters was finalized based on performance metrics.
  
## Dataset
Download the dataset from this link:-https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

