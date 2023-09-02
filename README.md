# Predictive Modeling of Customer Bookings

This Jupyter notebook contains code for predictive modeling of customer bookings. The code uses various packages for data manipulation, feature engineering, and machine learning.

## Exploratory Data Analysis

In this notebook, we perform exploratory data analysis (EDA) to better understand the dataset. Here are some of the key steps in the EDA process:

- We load the dataset using Pandas and use the `.head()` and `.info()` methods to examine the first few rows and get data descriptions.

- We convert the "flight_day" column to numerical values for analysis.

- We use the `.describe()` method to obtain summary statistics for numeric columns.

- We explore the dataset further with visualizations and metrics to gain insights.

## Data Preprocessing

We perform data preprocessing tasks, including:

- Mapping categorical values to numerical values for columns like "sales_channel" and "trip_type."

## Linear Regression Analysis

We conduct a linear regression analysis to predict the "booking_complete" target variable. Here's an overview of the steps:

- We define the independent variables (features) and the dependent variable (target).

- The dataset is split into training and testing sets.

- A Linear Regression model is created and trained on the training data.

- We evaluate the model's performance using Mean Squared Error (MSE) and R-squared (R2) values.

## Visualizing the Impact of Features

We visualize the impact of various features on booking completion using bar plots and scatter plots. These visualizations help us understand how different features influence the target variable.

## Visualizing the Impact of Trip Type

We visualize the impact of trip type on booking completion using a bar plot. This allows us to see how different trip types affect booking completion rates.

## Visualizing the Impact of Sales Channel

We visualize the impact of sales channel on booking completion using a bar plot. This helps us understand the role of different sales channels in customer bookings.

## Visualizing the Impact of Other Features

We create additional visualizations to understand the impact of features like "wants_extra_baggage" and "flight_duration" on booking completion.

## Repository Structure

- `customer_booking.csv`: The dataset used for analysis.

- `predictive_modeling.ipynb`: Jupyter notebook containing the code for this analysis.

## Getting Started

To run this analysis:

1. Clone the repository to your local machine.

2. Ensure you have Python and the required libraries (Pandas, Matplotlib, scikit-learn) installed.

3. Open and run the Jupyter notebook `predictive_modeling.ipynb`.

## Summary

This notebook provides a comprehensive analysis of customer bookings, including data exploration, preprocessing, linear regression modeling, and visualization of feature impacts. The insights gained from this analysis can help inform business decisions related to customer bookings.

For any questions or feedback, please contact [your email address].

