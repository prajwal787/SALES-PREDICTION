 
# Sales Prediction Project

This project uses machine learning to predict product sales based on advertising expenditure. By analyzing the impact of different advertising channels (TV, Radio, and Newspaper), the model provides insights to help businesses optimize their marketing strategies and maximize their return on investment (ROI).

## Table of Contents

- [Project Overview](#project-overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Actionable Insights](#actionable-insights)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview

In a competitive market, understanding the effectiveness of different advertising channels is crucial for optimizing marketing budgets. This project addresses this by building a machine learning model to predict sales based on advertising spending. The model helps identify the most effective channels and provides a tool for forecasting future sales.

## Objective

The main goals of this project are to:

- Build a reliable model to predict sales based on advertising budgets for TV, Radio, and Newspaper.
- Determine which advertising channels are most effective at driving sales.
- Provide data-driven insights to help with budget allocation.
- Develop a forecasting tool for predicting sales under different advertising scenarios.

## Dataset

The dataset used in this project consists of 200 instances, each representing a different market. The features include:

- **TV:** Advertising budget (in thousands of dollars) for TV.
- **Radio:** Advertising budget (in thousands of dollars) for Radio.
- **Newspaper:** Advertising budget (in thousands of dollars) for Newspaper.
- **Sales:** Product sales (in thousands of units).

The dataset is clean, with no missing values.

## Methodology

The project follows these steps:

1.  **Data Loading and Exploration:** The dataset is loaded, and exploratory data analysis (EDA) is performed to understand the relationships between the advertising channels and sales.
2.  **Data Preprocessing:** The data is prepared for modeling, and the dataset is split into training and testing sets.
3.  **Model Training:** Three different regression models are trained on the data:
    -   Linear Regression
    -   Random Forest Regressor
    -   Gradient Boosting Regressor
4.  **Model Evaluation:** The models are evaluated using Mean Squared Error (MSE) and R-squared to determine the best-performing model.

## Results

The **Gradient Boosting** model was the best-performing model for predicting sales.

| Model               | Mean Squared Error (MSE) | R-squared |
| ------------------- | ------------------------ | --------- |
| Linear Regression   | 2.91                     | 0.91      |
| Random Forest       | 1.44                     | 0.95      |
| **Gradient Boosting** | **1.26**                 | **0.96**  |

The high R-squared value (0.96) and low MSE (1.26) of the Gradient Boosting model indicate that it is highly accurate for predicting sales.

## Actionable Insights

-   **TV and Radio advertising** are the most effective channels for driving sales.
-   **Newspaper advertising** has a much weaker impact on sales.
-   The **Gradient Boosting model** is the most accurate for forecasting sales.

To maximize sales, it is recommended to:

1.  **Increase investment in TV and Radio advertising.**
2.  **Re-evaluate or reduce the budget for Newspaper advertising.**
3.  **Use the Gradient Boosting model for sales forecasting.**

 
