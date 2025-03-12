

# System Threat Forecaster: Machine Learning Project

## Project Overview
This project focuses on predicting potential security threats to computer systems based on their configuration, software, and usage patterns. Using machine learning techniques, we analyze various system attributes to identify machines that might be at risk of security threats.

## Dataset
The dataset contains information about various computer systems, including:
- System specifications and hardware details
- Security configurations and antivirus information
- Operating system details and version information
- User behavior patterns
- Temporal data (DateAS and DateOS)
- Target variable indicating whether a system is at risk (1) or not (0)

## Exploratory Data Analysis
The initial exploration of the data revealed:
- The dataset contains 100,000 records with 76 features
- There's a balanced distribution of the target variable (50.5% positive class)
- Several features show strong correlation with security threats
- Some features have missing values that require appropriate handling

## Methodology
The project follows a comprehensive machine learning pipeline:
1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   
2. **Feature Engineering**:
   - Creating temporal features from date columns
   - Developing security score metrics
   - Identifying feature interactions

3. **Model Development**:
   - Implementation of multiple classification algorithms
   - Hyperparameter tuning
   - Model evaluation and selection

4. **Ensemble Methods**:
   - Combining predictions from multiple models
   - Boosting and bagging techniques

## Models Implemented
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Stacking Ensemble

## Results
The models were evaluated using accuracy, precision, recall, and AUC metrics. The best performing model achieved a score of [0.62] on the test set.

## Requirements
- Python 3.12
- Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, XGBoost, LightGBM, Seaborn


## Future Work
- Implement more sophisticated feature engineering
- Explore deep learning approaches
- Develop a real-time threat detection system

## Author
Roll Number: 22f3001943

