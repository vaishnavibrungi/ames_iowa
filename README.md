# **Problem Statement**

At our real estate investment firm, apart from providing investors with new and refurbished investment properties, we also do consultation service to sellers who want to sell their homes by estimating sale price, finding buyers, taking care of the documentation process until the seller handovers key to the buyer. We have been given a list of clients who are willing to sell their homes in Ames city in  Iowa. This analysis seeks to predict the sale price of homes in Ames. This analysis also aims to list down top factors that affect sale price in Ames which can be used as a checklist in the future if any client from these locations approaches us seeking consultation service to sell their property.


# **Summary**

## Train  Data Import and Cleaning 
  * Missing values were fixed 
  * Fixed column names by replacing spaces with underscores    and  converting them to lower case 
  * Cleaned up data types 
  * Created and modified features using feature engineering 
  * Fixed outliers

## Test Data Import and Cleaning
  * Missing values were fixed
  * Fixed column names by replacing spaces with underscores and converting them to lower case
  * Cleaned up data types
  * Created and modified features using feature engineering

## Exploratory Data Analysis

Descriptive statistics were generated for Train data

## Data Visualization

Histogram, bar plots and scatter plots were used to analyze the data and correlation

# **Data Dictionary**

A complete overview of the data can be found here
[**Data Description**](https://www.kaggle.com/c/dsir-bluebird-project-2-regression-challenge/data)

|    Type 	|                                                              Definition                                                              	|
|:----------:	|:-------------------------------------------------------------------------------------------------------------------------------------:	|
|   Nominal  	|                            variables that   have two or more categories, but which do not have an intrinsic order                     	|
|   Ordinal  	|         variables   that have two or more categories just like nominal variables only the   categories can also be ordered or ranked. 	|
|  Discrete  	|                                           variables, wherein the values can be obtained by counting                                   	|
| Continuous 	|                                                       variables that measure something                                                	|


# **Conclusions**

The objective of the analysis was to build a model to predict housing prices of different residences in Ames, IA. Our best model resulted in an RMSE of 26109.34, which translates to an error of  ~±$26109 for the average-priced house.
The factors seen as most important or as strongest predictors through our model were :
   * Overall House Quality
   * Living Area Square footage
   * Basement Square Footage
   * Garage Square Footage
   * Garage Car Capacity(i.e. number of cars garage can accommodate)
   * Number of Fireplaces
   * Year Built(i.e. The more recent is the house built, the higher is the sale price)
   * Total Number of Bathrooms
   * Area of Exterior Masonry
