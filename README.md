# Hypothesis Testing Fundamentals

## Project Overview

This project demonstrates the fundamentals of statistical hypothesis
testing using Python, Pandas, and SciPy.

The Titanic dataset was used to perform three different hypothesis tests.

## Objective

The objective of this project is to understand how to:

- Formulate null and alternative hypotheses
- Select an appropriate statistical test
- Calculate test statistics
- Calculate p-values
- Interpret statistical significance
- Make decisions using a significance level of 0.05

## Tools and Technologies

- Python
- Pandas
- NumPy
- SciPy
- Seaborn
- Matplotlib
- Google Colab / Jupyter Notebook

## Dataset

Titanic passenger dataset.

The dataset contains information such as:

- Passenger age
- Fare
- Sex
- Survival status
- Passenger class

## Hypothesis Tests

### 1. One-Sample t-Test

Research Question:

Is the average age of Titanic passengers significantly different
from 30 years?

Null Hypothesis:
The population mean age is 30 years.

Alternative Hypothesis:
The population mean age is different from 30 years.

### 2. Independent Two-Sample t-Test

Research Question:

Is there a significant difference in average fare between survivors
and non-survivors?

Null Hypothesis:
The mean fare is equal between the two groups.

Alternative Hypothesis:
The mean fare differs between the two groups.

### 3. Chi-Square Test of Independence

Research Question:

Is passenger sex significantly associated with survival?

Null Hypothesis:
Sex and survival are independent.

Alternative Hypothesis:
Sex and survival are associated.

## Significance Level

The significance level used throughout the project is:

α = 0.05

Decision Rule:

- p-value < 0.05 → Reject H0
- p-value >= 0.05 → Fail to Reject H0

## Conclusion

The project demonstrates how statistical hypothesis testing can be used
to investigate differences and associations within sample data.

The results should be interpreted statistically and should not
automatically be considered evidence of causation.

## Author

Data Science Internship Project
