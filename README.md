# Understanding Factors Behind US Home Prices: A Multiple Linear Regression Model

## Overview

This project explores the factors influencing home prices over the past two decades using the S&P Case-Schiller Home Price Index as a proxy. The primary analytical tool used is multiple linear regression, providing insights into the relationships between home prices and various independent variables.

## Key Components

 **GitHub Repository Structure:**
   - [Raw Data](https://github.com/dipboruah/US-Home-Prices-Analysis/tree/main/Raw%20Datasets).
   - [Metadata](https://github.com/dipboruah/US-Home-Prices-Analysis/blob/main/Metadata.csv)
   - [Cleaned Data](https://github.com/dipboruah/US-Home-Prices-Analysis/blob/main/US_Data_Cleaned.csv)
   - [Regression Model](https://github.com/dipboruah/US-Home-Prices-Analysis/blob/main/Regression_Model.ipynb)
   - [Final Report](https://github.com/dipboruah/US-Home-Prices-Analysis/blob/main/Final_Report.pdf)

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

5. **Future Work:**
   - Addition of other Machine learning models to enhance the prediction accuracy.
   - Additional factors can be added for model enhancement.


## Results and Top 5 Factors Influencing Home Prices


| Name                        | Regression Coefficients    | Interpretation                                              |
| --------------------------- | ---------- | ----------------------------------------------------------- |
| New One Family House        | 0.157518   | An increase in the number of new one-family houses is associated with the most significant predicted increase in home prices.                       |
| GDP                         | 0.120058   | An increase in the Gross Domestic Product is associated with a significant predicted increase in home prices.                                        |
| Population                  | 0.115109   | An increase in population is associated with a notable predicted increase in home prices.                                                         |
| Employed                    | -0.116458  | A decrease in the number of employed individuals is associated with a significant predicted decrease in home prices.                              |
| Mortgage Rate               | -0.024249  | An increase in mortgage rates is associated with a decrease in home prices.                                                                      |


   - R squared value: 0.9881408274261253.
   - The model explains 98% of the variability in home prices, providing a robust fit to the data.


