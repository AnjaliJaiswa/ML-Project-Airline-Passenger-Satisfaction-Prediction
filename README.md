# Airline Passenger Satisfaction Prediction

This project aims to predict passenger satisfaction with airline services using various machine learning techniques. By analyzing a dataset containing demographic information, travel details, and satisfaction ratings, the project identifies key factors influencing satisfaction levels and builds predictive models to assist airlines in improving their services and enhancing customer experience.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Objectives](#project-objectives)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Selection](#feature-selection)
- [Models Used](#models-used)
- [Results](#results)
- [License](#license)

## Overview

The airline industry is highly competitive, with a continuous need for airlines to enhance customer satisfaction and loyalty. This project focuses on predicting passenger satisfaction by utilizing machine learning techniques on a comprehensive dataset of passenger demographics, travel details, and satisfaction ratings.

## Dataset

The dataset consists of two files: `train.csv` and `test.csv`. The training dataset contains 103,904 rows, while the test dataset includes 17,965 rows. Each row represents a passenger's feedback and demographic information after a flight.

### Features

- **Demographic Information**: Gender, Age, etc.
- **Travel Details**: Customer Type, Type of Travel, Class, Flight Distance, etc.
- **Satisfaction Ratings**: Inflight Wi-Fi Service, Seat Comfort, Food and Drink, Cleanliness, and more.
- **Target Variable**: Satisfaction level (`satisfied` or `neutral or dissatisfied`).

## Project Objectives

1. Explore the dataset to understand its structure and characteristics.
2. Preprocess the data, including handling missing values and encoding categorical variables.
3. Perform feature selection to identify relevant features for predicting passenger satisfaction.
4. Train and evaluate various machine learning models: Random Forest, Logistic Regression, MLP Classifier, and Gradient Boosting Classifier.
5. Analyze model performance and identify the most effective approach for predicting passenger satisfaction.

## Data Preprocessing

- Handled missing values using imputation techniques.
- Encoded categorical variables using label encoding and one-hot encoding.
- Performed feature scaling and selection using Random Forest for feature importance.

## Exploratory Data Analysis

- **Histograms**: Analyzed the distribution of numerical variables like Age.
- **Bar Charts**: Visualized the distribution of categorical variables like Gender and Customer Type.
- **Box Plots**: Compared distributions across different categories (e.g., Flight Distance by Class).
- **Scatter Plots**: Explored relationships between numerical variables.
- **Frequency Distribution**: Analyzed the distribution of satisfaction levels.

## Feature Selection

Feature importance was determined using Random Forest, highlighting key factors such as Online Boarding, Inflight Wi-Fi Service, and Type of Travel.

## Models Used

1. **Random Forest Classifier**: Achieved high accuracy with significant insights from feature importance.
2. **Logistic Regression**: Provided a baseline with reasonable accuracy.
3. **MLP Classifier**: Demonstrated strong predictive capabilities with a complex model architecture.
4. **Gradient Boosting Classifier**: Utilized ensemble learning for improved performance.

## Results

- **Random Forest Classifier**: Accuracy - 96%
- **Logistic Regression**: Accuracy - 85.91%
- **MLP Classifier**: Accuracy - 95.13%
- **Gradient Boosting Classifier**: Accuracy - 93.10%

The MLP Classifier showed the strongest performance in predicting passenger satisfaction, closely followed by the Random Forest Classifier.
## License
This project is licensed under the MIT License. See the LICENSE file for more details.










