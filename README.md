# Introduction to Linear Regression - Recap

## Introduction

In this section you learned about a statistical model, linear regression, that can be used to model the relationship between an independent and dependent variable.

## Key Takeaways

* ***Statistical modeling*** combines statistics and data to draw conclusions about real-world relationships
  * When defining a statistical model, you use data understanding to define an ***independent variable*** (x) and a ***dependent variable*** (y)
* A ***simple linear regression*** model defines the relationship between x and y as a straight line, ***y = mx + c***
  * The fitted model ***parameters*** are the best-fit values for m (slope) and c (intercept)
  * The ***least-squares*** method allows you to calculate a "closed-form" best fit by minimizing the model error
* You can ***evaluate*** linear regression models overall, as well as their parameters
  * The ***F-statistic*** indicates whether the model is statistically significant overall
  * ***R-Squared*** (coefficient of determination) describes the amount of variance in the dependent variable that is explained by the model
  * Parameters have ***coefficient*** values that describe the change in the dependent variable associated with a unit change in the independent variable, as well as ***p-values*** and ***confidence intervals*** created using the t-distribution
* ***StatsModels*** is a useful library for fitting and evaluating linear regression models, using the `OLS` class
  * You can also use StatsModels to find the model ***residuals***, i.e. the differences between the true values and the values predicted by the model
