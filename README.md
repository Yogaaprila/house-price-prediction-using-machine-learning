# House Price Prediction Using Machine Learning

![Alt Text](pictures/wkw4_uxcu_210127.jpg)

## Background 
Determining a competitive house price is a challenge for sellers and real estate agents because house prices are influenced by various factors such as size, location, facilities, and market conditions.
Manual processes often fall short in addressing this complexity. As a data scientist at a proptech startup, we adopt a machine learning-based approach to develop a house price prediction platform. This platform is designed to provide accurate price estimates for new data, including in markets that have not been previously analyzed.
Through this platform, we aim to assist stakeholders, such as sellers and real estate agents, in determining competitive house prices more efficiently and data-driven.

## Goal 
Develop a machine learning platform capable of predicting house prices with high accuracy.

## Objective
1. Analyze factors influencing house prices, such as size, facilities, and various other aspects, using Exploratory Data Analysis (EDA).
2. Build and train machine learning regression model to generate accurate house price predictions based on historical data.
3. Determine which features have an impact on the increase in house prices.

## Tool
Python Programming Language
JupyerLab / Jupyter Notebook

## Evaluation Metric
Mean Absolute Percentage Error (MAPE).
R-Square.

## Dataset
| **Feature**            | **Description**                                                                                       |
|-------------------------|-------------------------------------------------------------------------------------------------------|
| **Square_Footage**      | The size of the house in square feet. Larger homes typically have higher prices.                      |
| **Num_Bedrooms**        | The number of bedrooms in the house. More bedrooms generally increase the value of a home.            |
| **Num_Bathrooms**       | The number of bathrooms in the house. Houses with more bathrooms are typically priced higher.         |
| **Year_Built**          | The year the house was built. Older houses may be priced lower due to wear and tear.                  |
| **Lot_Size**            | The size of the lot the house is built on, measured in acres. Larger lots tend to add value to a property. |
| **Garage_Size**         | The number of cars that can fit in the garage. Houses with larger garages are usually more expensive. |
| **Neighborhood_Quality**| A rating of the neighborhood’s quality on a scale of 1-10, where 10 indicates a high-quality neighborhood. Better neighborhoods usually command higher prices. |
| **House_Price**         | The price of the house, which is the dependent variable you aim to predict.                           |

## 1. Exploratory Data Analysis
### 1.1 Summary Statistics

### 1.2 Univariate Analysis
#### 1.2.1 Boxplot
#### 1.2.2 Histogram and Distribution Line
#### 1.2.3 Distibution of Number of Bedroom, Number of Bathroom, Garage Size, and Neighborhood Quality.

### 1.3 Bivariate Analysis
#### 1.3.1 Number of Bedrooms, Number of Bathroom, Garage Size, and Neighborhood Quality vs House Price
#### 1.3.2 House Price Trend by Year Built

### 1.4 Multivariate Analysis
#### 1.4.1. Heatmap Correlation
#### 1.4.2 Pairplot

## 2. Modeling
### 2.1 Fit Model
### 2.2 Evaluation Metrics
### 2.3 Feature Impact
### 2.4 Business Recommendation

