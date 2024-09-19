# Predicting Hospital Length of Stay Using Machine Learning

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Deployment](#model-deployment)


## Project Overview
Predicting Hospital Stay Using Machine Learning project focuses on predicting patients' hospital length of stay 
using machine learning techniques. By analyzing various patient data, including demographic, clinical, and hospital-related features, the project aims 
to develop models that can forecast stay durations with greater precision. This prediction is crucial for optimizing hospital resource management, 
improving patient outcomes, and reducing costs. The project leverages advanced machine learning algorithms and  hyperparameter tuning technique to 
ensure robust and reliable predictions, ultimately leading to a better healthcare planning and efficiency.

![Picture](lhs2.jpg)


## Dataset Overview
The data set contains patients' demography with hospital-related features. Attached is screenshot of the data overview.

![Data Overview](Data_overview.jpg)


## Data Preprocessing
Data preprocessing was done to prepare the data for modelling
- **Handle missing values**: Ensured that all missing values in the dataset were properly addressed. No Missing values 
- **Remove duplicates**: Checked for duplicate values to avoid redundancy. No duplicate was found in the dataseta.
- **Scale numerical variables**: The numerical variables in the dataset were scaled to ensure consistent scaling.
- **Encode categorical variables**: Categorical features were encoded 


## Model Building
5 machine learning classifiers:
- Logistic Regression
- Bagging Classifier
- Random Forest Classifier
- Naive Bayes 
- CatBoost Classifier were imported
- The classifiers were trained on the training dataset, and evaluated on the test subset of the dataset.

## Model Deployment
The model was deployed using Streamlit

![Model Picture](lhs_image.jpg)
