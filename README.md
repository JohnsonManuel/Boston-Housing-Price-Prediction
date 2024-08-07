# Boston Housing Price Prediction

This project involves performing linear regression on the Boston Housing dataset to predict housing prices. The dataset includes 13 features about housing in Boston, and the goal is to predict the median value of owner-occupied homes (`MEDV`).

## Project Overview

- **Objective:** Predict housing prices using linear regression.
- 
- **Dataset:** [Boston Housing Dataset](https://scikit-learn.org/1.0/modules/generated/sklearn.datasets.load_boston.html)
- **Tools Used:** 
  - Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn.

## Features in the Dataset

The dataset includes the following features:

1. **CRIM:** Per capita crime rate by town
2. **ZN:** Proportion of residential land zoned for lots over 25,000 sq. ft.
3. **INDUS:** Proportion of non-retail business acres per town
4. **CHAS:** Charles River dummy variable (1 if tract bounds river; 0 otherwise)
5. **NOX:** Nitric oxides concentration (parts per 10 million)
6. **RM:** Average number of rooms per dwelling
7. **AGE:** Proportion of owner-occupied units built prior to 1940
8. **DIS:** Weighted distances to five Boston employment centers
9. **RAD:** Index of accessibility to radial highways
10. **TAX:** Full-value property tax rate per $10,000
11. **PTRATIO:** Pupil-teacher ratio by town
12. **B:** \(1000(Bk - 0.63)^2\) where \(Bk\) is the proportion of Black residents by town
13. **LSTAT:** % lower status of the population
14. **MEDV:** Median value of owner-occupied homes in $1000s (Target)

## Steps Followed

1. **Data Loading and Preprocessing:**
   - Load the dataset using scikit-learn and convert it into a Pandas DataFrame.
   - Display the first few rows to understand the dataset structure.

2. **Exploratory Data Analysis (EDA):**
   - Generate summary statistics to understand feature distributions.
   - Visualize relationships between features and the target variable using pairplots and correlation heatmaps.

3. **Feature Selection:**
   - Identify significant features based on correlation with the target variable.
   - Address multicollinearity by examining feature correlations.

4. **Model Training:**
   - Split the dataset into training and testing sets (80-20 split).
   - Train a linear regression model on the training data.

5. **Model Evaluation:**
   - Make predictions on the testing set.
   - Calculate performance metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE).
   - Visualize actual vs. predicted values.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Boston-Housing-Price-Prediction.git
   cd Boston-Housing-Price-Prediction
