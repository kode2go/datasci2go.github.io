---
title: Data Science 2 Go
layout: template
filename: index
--- 

* TOC
{:toc}

## Welcome to Data Science 2 Go

![image](https://user-images.githubusercontent.com/29664888/127746783-bce7bed8-6e7d-4cab-b07d-494e16d8ac88.png)

![image](https://user-images.githubusercontent.com/29664888/127746796-acd61ea0-759a-4714-b4ec-6853f8e5dd5c.png)

# Statistics and Knowing Your Data

Statistics is the science of analyzing, reviewing and conclude data. In order to do that you must also be able to analyze your data and it is important to know what type of data we are dealing with.

Some basic statistical numbers include:

* Mean, median and mode
* Minimum and maximum value
* Percentiles
* Variance and Standard Deviation
* Covariance and Correlation
* Probability distributions

The Python language has many built-in functionalities, in addition to libraries for the exact purpose of statistical analysis.

You will learn about these features, and how to use them in the next chapters.

## Types of Data Variables

See the table below for the various types of data variables we will be working with:

![image](https://user-images.githubusercontent.com/29664888/159611320-84663ee7-b010-40d3-a0cc-94f133c37b27.png)

We need to know what type of data we are dealing with so we can visualize and plot the appropriate figures to analyze them. This site helps to breakdown the typical figures you would need based on the data type you have:

https://www.data-to-viz.com/

![image](https://user-images.githubusercontent.com/29664888/159611666-b421f53c-4165-42b1-8298-b3d76ceea295.png)

For example let us analyze this table below:

![image](https://user-images.githubusercontent.com/29664888/159611875-fe3d185a-9c1a-4549-8a82-88b70b8bf59e.png)

* Gender: categorical
* Sleep: numerical, continuous
* Bedtime: categorical, ordinal
* Countries: numerical, discrete
* Dread: categorical, ordinal (could be numerical)

Lastly, what would telephone area code be like `8001`? 

We can't do any normal math with it so it must be categorical, and it is also not ordered so it must be nominal.

## 1.  Data Cleaning
It is very important to get rid of the irregularities and clean the data after sourcing it into our system.
Irregularities are of different types of data.
* Missing Values
* Incorrect Format
* Incorrect Headers
* Anomalies/Outliers

## 2. Bivariate Analysis

When we talk about bivariate analysis, it means analyzing 2 variables. Since we know there are numerical and categorical variables, there is a way of analyzing these variables as shown below:

![image](https://user-images.githubusercontent.com/29664888/176466124-55cc62cd-ebef-41d0-bb7b-7f25010db338.png)

## 3. Numerical vs. Numerical

For this case we can use plots like Scatter plots, Line plots, Heatmap for correlation, and Joint plots

## 4. Categorical vs. Numerical

For this case we can use Bar charts, Violin plots, Categorical box plots, and swarm plots

## 5. Two Categorical Variables

For this case we can use Bar charts, Grouped bar charts, and Point plots

## 6. Normalizing and Scaling

Often the variables of the data set are of different scales i.e. one variable is in millions and others in only 100. For e.g. in our data set Income is having values in thousands and age in just two digits. Since the data in these variables are of different scales, it is tough to compare these variables.

Feature scaling (also known as data normalization) is the method used to standardize the range of features of data. Since the range of values of data may vary widely, it becomes a necessary step in data preprocessing while using machine learning algorithms.

In this method, we convert variables with different scales of measurements into a single scale. Standard scaler normalizes the data using the formula (x-mean)/standard deviation. We will be doing this only for the numerical variables.

