# Understanding Factors Behind US Home Prices: A Multiple Linear Regression Model

## Overview

This project explores the factors influencing home prices over the past two decades using the S&P Case-Schiller Home Price Index as a proxy. The primary analytical tool used is multiple linear regression, providing insights into the relationships between home prices and various independent variables.

## Key Components

1. **Data Collection:**
   - Data sourced from ["https://fred.stlouisfed.org/"](https://fred.stlouisfed.org/).
   - Time span: Last 20 years.
   - Data frequency: [weekly, monthly, Quarterly yearly].

2. **Data Cleaning and Preprocessing:**
   - Handling missing values, detecting and dealing with outliers.
   - Preprocessing steps for regression analysis.

3. **Feature Considered:**
   - Employed, New House Supply Rate, Mortgage Rate, Unemployment Rate, Consumer Credit rate, Population, Personal Income, GDP, Houseownership Rate, New One Family House, Inflation Rate, Floor Area West Census Region
   - Influence of domain knowledge on feature choices.

4. **Model Building:**
   - Multiple linear regression model.
   - Standardization of data
   - Split data into training and testing datasets.
   - Training and validation process of the model
   - Feature selection with Weights.

5. **Results and Interpretation:**
   - R squared value: 0.9881408274261253.
   - The model explains 0.98% of the variability in home prices, providing a robust fit to the data.

6. **GitHub Repository Structure:**
   - [Raw Data](https://github.com/dipboruah/US-Home-Prices-Analysis/tree/main/Raw%20Datasets).
   - README with instructions for code execution.

7. **Visualizations:**
   - Scatter plots, regression diagnostics, feature importance graphs.
   - Visualizations to enhance understanding.

8. **Future Work:**
   - Potential avenues for future research.
   - Additional factors for model enhancement.

9. **Conclusion:**
    - Key findings and implications.
    - Value of the analysis in understanding home price dynamics.
