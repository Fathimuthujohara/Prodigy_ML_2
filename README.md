# Housing Price Prediction

## Linear Regression

### Overview

This project aims to predict housing prices using multiple linear regression. The dataset contains various features such as price, number of bedrooms, number of bathrooms, sqft living, city, street, and other relevant factors. The goal is to identify the key variables that influence house prices and build a predictive model.

### Table of Contents

1. [Data Preprocessing](#data-preprocessing)
2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Feature Selection with RFE](#feature-selection-with-rfe)
4. [Building the Linear Regression Model](#building-the-linear-regression-model)
5. [Model Evaluation](#model-evaluation)
6. [Conclusion](#conclusion)

---

## Data Preprocessing

Data preprocessing is essential to prepare the data for analysis and modeling. It involves cleaning and transforming the raw data to ensure it is suitable for building a predictive model.

### Steps Involved:

1. **Data Collection**
   - Gather data from reliable sources, ensuring the dataset includes features such as property area, number of bedrooms, bathrooms, parking spaces, etc.

2. **Data Cleaning**
   - **Handling Missing Values**: Identify and handle missing values by removing rows/columns with excessive missing data or imputing missing values using appropriate methods (e.g., mean, median, mode).
   - **Removing Duplicates**: Ensure no duplicate records are present in the dataset.
   - **Correcting Errors**: Fix any inconsistencies or errors in the data, such as correcting typos and resolving incorrect entries.

3. **Data Transformation**
   - **Encoding Categorical Variables**: Convert categorical variables into numerical values using techniques like one-hot encoding.
   - **Scaling**: Normalize or standardize numerical features to ensure all variables are on a similar scale.

## Exploratory Data Analysis (EDA)

EDA helps in understanding the underlying patterns and relationships in the data. It involves generating statistical summaries and visualizations to gain insights into the dataset.

### Steps Involved:

1. **Statistical Summary**
   - Generate a statistical summary of the dataset to understand the distribution of numerical and categorical features.

2. **Data Visualization**
   - **Scatter Plots**: Explore relationships between independent variables and the target variable (house price).
   - **Heatmaps**: Examine correlations between different features.

## Feature Selection with RFE

Recursive Feature Elimination (RFE) is used to select the most important features for the model. It iteratively removes the least significant features based on the estimator's coefficients.

### Steps Involved:

1. **Model Selection**
   - Choose a base model for RFE, such as Linear Regression.

2. **Applying RFE**
   - Use RFE to select the top features that have the highest impact on the target variable.

3. **Evaluating Selected Features**
   - Review and validate the selected features to ensure they make sense from a domain knowledge perspective.

## Building the Linear Regression Model

After selecting the significant features, the next step is to build and train the multiple linear regression model.

### Steps Involved:

1. **Splitting the Data**
   - Split the dataset into training and testing sets to evaluate the model's performance on unseen data.

2. **Training the Model**
   - Fit the linear regression model using the training data.

3. **Making Predictions**
   - Use the trained model to make predictions on the test data.

## Model Evaluation

Evaluating the model's performance is crucial to understand its predictive power and accuracy.

### Metrics Used:

1. **Mean Squared Error (MSE)**
2. **R-squared (R²)**

### Steps Involved:

1. **Calculating Metrics**
   - Compute the evaluation metrics to assess the model's accuracy and performance.

2. **Residual Analysis**
   - Analyze the residuals to check for any patterns that indicate model inadequacies.

