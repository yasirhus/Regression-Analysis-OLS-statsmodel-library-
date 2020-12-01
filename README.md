# Regression-Analysis-OLS-statsmodel-library-
The project is about building an Linear Regression (OLS) model to measure the relationship between a dependent variable (Salary) and an independent variable (Yearsofexperience). The aim of building this model is to understand the concept of Ordinary Least Square and its deployment on a aprticular dataset. Moroever, it is to be measured that how much salaries of individuals being affected by the years of experience they have. Moreover, it is also being examined in the model that how much variation in Slaries is being explained by the Years_of_Experinece.  
## Getting Started
The project is being deployed on Jupyter (.ipynb) as I find it convenient and interesting way to program. 
### Prerequisities
To run a linear regression model on jupyter, one need to install few libraries such as numpy, pandas and statesmodel.api and import these libraries to initialize the code. 
```bash
import numpy as np

import pandas as pd

import statsmodels.api as sm
```
### importing data 
To build a regression model, you need to import data file from local file that is either in [.csv] format or in [.txt] or in any other format. 

### Visualizing the data.
Regression model has some basic properties and to check some of the properies such as linearity of the data, we can simply plot the variables to see if both independent and dependent variables are linearly correlated or not andf this job can be done using scatter plot (it plots pairs of data). There are some other plots too that can help us to understand the behavior of the data. Here, I visulaized the data using scatter plot which states explain that the data is linearly correlated and we can mode on towards the model.

### Building Model 

Once you are satisfied with the data and data is well preprocessed, you can move towards next step which is building the model. 

###Intepretting the Analysis 
Last step, but very important i.e interpretting the model. If we look at the model, our independent variable YearsofExperinece plays an important role in the increase in salary. A years increase in experinece will icrease 9449 Euros in salary or vice versa. The next step is to see how fit the model is that can be analyzed using #R square. Here in my model that value of R-Square is 0.957 which states that Years of experinece explains 95 percent variation in  

