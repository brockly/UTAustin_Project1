# FoodHub Data Analysis Project

## Overview
This repository contains the Python-based data analysis project titled **\"FoodHub Data Analysis\"**, completed as part of the Python Foundations course offered through the Great Learning program in collaboration with UT Austin.

## Project Context
With the growing number of restaurants in New York and the increasing reliance on online food delivery services by students and busy professionals, FoodHub, a food aggregator company, aims to optimize its operations by analyzing order data. FoodHub's smartphone app connects customers to multiple restaurants, assigning delivery personnel to pick up and deliver orders efficiently.

The purpose of this analysis is to provide actionable insights that can help FoodHub enhance customer experience and improve their overall business operations.

## Objective
As a Data Scientist at FoodHub, the main task was to analyze order data collected through the company's online portal. The analysis aimed at answering critical business questions to understand restaurant demand, customer preferences, and operational performance.

## Dataset Description
The dataset contains various attributes related to food orders placed through the FoodHub app. Below is a detailed description of the dataset:

| Column Name            | Description                                                                                                 |
|------------------------|-------------------------------------------------------------------------------------------------------------|
| `order_id`             | Unique identifier for each order placed                                                                     |
| `customer_id`          | Identifier for the customer who placed the order                                                            |
| `restaurant_name`      | Name of the restaurant from which the food was ordered                                                     |
| `cuisine_type`         | Type of cuisine ordered                                                                                    |
| `cost_of_the_order`    | Cost of the food order                                                                                     |
| `day_of_the_week`      | Indicates if the order was placed on a weekday (Mon-Fri) or weekend (Sat-Sun)                              |
| `rating`               | Customer rating for the order, out of 5                                                                    |
| `food_preparation_time`| Time (in minutes) taken by the restaurant to prepare the food                                              |
| `delivery_time`        | Time (in minutes) taken by the delivery person to deliver the food                                         |

## Analysis Performed
- Exploratory Data Analysis (EDA)
- Identifying top-performing restaurants and cuisine types
- Analysis of order costs and ratings
- Evaluating differences in order patterns between weekdays and weekends
- Assessing food preparation and delivery times

## Tools and Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Use
1. Clone this repository to your local system.
```bash
git clone [repository_url]
```

2. Open and run the provided Python notebook file (`.ipynb`) using Jupyter Notebook to review and reproduce the analysis steps and results.

## Contributions
Feel free to fork this repository, suggest improvements, or report any issues found during analysis.

---

**Author:** Alex Brockman 
**Course:** Python Foundations, Great Learning @ UT Austin  
**Date:** March 2024

