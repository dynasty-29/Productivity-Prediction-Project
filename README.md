
# Productivity-Prediction-Project
![alt text][logo]
[logo]: https://idsb.tmgrup.com.tr/2015/12/15/GenelBuyuk/1450122285272_rs.jpg

## Introduction

The garment industry deals with the production of different types of clothing. It is a trillion-dollar industry on the global scale (reference), and is a labor- and capital-intensive industry. Workforce productivity in general refers to a measurement of goods and/or services produced by a group of workers within a given time period. High productivity levels by a team translate to higher profits, and are an indication of efficient use of the inputs in the production process. Worker productivity in the garment industry should therefore be maximized as it is a key factor to its success.

## Objective

The main objective of the study is to create a model that can predict the level of productivity of employee teams in the garment industry.

### Problem Statement

Low workforce productivity in a company can lead to reduced profitability, increased conflict, high employee turnover, and a lack of motivation. It is therefore important for a company to be able to track and predict its levels of productivity and investigate the factors that influence this.

### Metrics for success
  * Visualising the relationships between actual productivity and the predictor variables.
  * Building a model that can predict employee productivity (Best model should have the lowest RMSE).
  * Identifying the top factors influencing the productivity level of employees.
  * Deployment of best model []
### Recording experimental design
  * Determine the main objectives
  * Load and preview the dataset.
  * Understand the data.
  * Prepare the dataset - Identify outliers, anomalies, duplicates, missing values, and determine how deal with them etc.
  * Carry out univariate analysis, bivariate analysis, and modelling.
  * Challenge the solution.
  * Conclusion and recommendations
  
#### Data source and column explanations

The dataset is from UCI machine learning repository and can be accessed [here](https://archive-beta.ics.uci.edu/ml/datasets?name=Productivity%20Prediction%20of%20Garment%20Employees).

#### Column definitions:

  1. date : Date in MM-DD-YYYY

  2. day : Day of the Week

  3. quarter : A portion of the month. A month was divided into four quarters

  4. department : Associated department with the instance

  5. team_no : Associated team number with the instance

  6. no_of_workers : Number of workers in each team

  7. no_of_style_change : Number of changes in the style of a particular product

  8.targeted_productivity : Targeted productivity set by the Authority for each team for each day.

  9. smv : Standard Minute Value, it is the allocated time for a task

  10. wip : Work in progress. Includes the number of unfinished items for products

  11. over_time : Represents the amount of overtime by each team in minutes

  12. incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.

  13. idle_time : The amount of time when the production was interrupted due to several reasons

  14. idle_men : The number of workers who were idle due to production interruption

  15. actual_productivity : The actual % of productivity that was delivered by the workers. It ranges from 0-1.


