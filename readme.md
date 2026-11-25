# Practical 7 – Understanding Regression with T-Test and ANOVA

## Aim

To study the relationship between teachers' gender, age, beauty scores, and teaching evaluation scores using regression analysis, T-test, ANOVA, and correlation.

## Objectives

- To understand regression analysis and its application in statistics.
- To examine whether gender affects teaching evaluation scores using a T-test.
- To study whether instructors' beauty scores differ according to age groups using ANOVA.
- To examine the relationship between teaching evaluation scores and beauty scores.
- To understand the interpretation of regression coefficients and p-values.
- To draw conclusions from statistical results using the TeachingRatings dataset.

## Dataset

The TeachingRatings dataset is used for this practical. It contains information about instructors, including their gender, age, beauty ratings, and teaching evaluation scores.

**Dataset URL:**

https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/AER/TeachingRatings.csv

## Libraries Used

- **Pandas** – For loading and manipulating the dataset.
- **SciPy** – For statistical calculations and hypothesis testing.
- **Statsmodels** – For regression analysis and ANOVA.

## Questions and Analysis

### Q1. Regression with T-Test

A regression model was created to examine whether gender affects teaching evaluation scores.

The model used was:

`eval ~ C(gender)`

The regression results showed that male professors had an average evaluation score approximately 0.168 points higher than female professors.

The p-value was 0.001, which is less than the significance level of 0.05. Therefore, the difference in evaluation scores between genders was statistically significant.

The R-squared value of 0.022 indicated that gender explained approximately 2.2% of the variation in teaching evaluation scores.

### Q2. Regression with ANOVA

The instructors were divided into three age groups:

- 40 and younger
- 41 to 56
- 57 and older

A regression model was created to examine whether beauty scores differed across these age groups.

The ANOVA results showed a statistically significant difference in beauty scores among the age groups.

The p-value was approximately 4.32 × 10⁻⁸, which is less than 
