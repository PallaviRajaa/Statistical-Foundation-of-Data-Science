# Probability and Hypothesis Testing Using Python

## Project Overview

This project focuses on applying probability distributions and hypothesis testing techniques to real-world statistical problems using Python.

The Teaching Ratings Dataset is used to calculate probabilities related to teaching evaluation scores. A two-tailed Z-test is also performed to compare the average points scored by regional basketball players with the historical professional mean.

## Dataset

The dataset used in this project is the Teaching Ratings Dataset provided by IBM Skills Network.

**Dataset URL:**  
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/teachingratings.csv

## Libraries Used

- **Pandas** – For loading and handling the dataset.
- **Matplotlib** – For data visualization.
- **SciPy** – For probability calculations and statistical testing.

## Questions and Analysis

### Q1. Probability of Receiving an Evaluation Score Greater Than 4.5

- Assumed a normal distribution of teaching evaluation scores.
- Used the mean (3.998) and standard deviation (0.554).
- Calculated the Z-score for an evaluation score of 4.5.
- Found the probability of receiving a score greater than 4.5 using the standard normal distribution.

**Result:** Approximately 18.24%.

### Q2. Probability of Receiving an Evaluation Score Between 3.5 and 4.2

- Calculated the Z-scores for evaluation scores of 3.5 and 4.2.
- Used the cumulative distribution function (CDF) of the normal distribution.
- Calculated the probability of a score falling between the two values.

**Result:** Approximately 46%.

### Q3. Two-Tailed Hypothesis Test – Basketball Players

A two-tailed Z-test was conducted to determine whether the average points scored by regional basketball players differed significantly from the historical professional mean.

**Given:**

- Population mean = 12 points
- Population standard deviation = 5.5
- Sample mean = 10.7 points
- Sample size = 36
- Significance level = 0.05

The standard error and Z-score were calculated, followed by the p-value.

**Result:** The p-value is approximately 0.156.

Since the p-value is greater than the significance level of 0.05, we fail to reject the null hypothesis. There is insufficient statistical evidence to conclude that the average points scored by regional basketball players differs from the historical professional mean.

## Concepts Covered

- Normal Distribution
- Z-score
- Probability Calculation
- Cumulative Distribution Function (CDF)
- Standard Error
- Null and Alternative Hypotheses
- Two-Tailed Z-Test
- P-value
- Statistical Significance

## Tools and Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib
- SciPy

## Conclusion

This practical demonstrates how probability and hypothesis testing can be performed using Python. It helps understand the application of the normal distribution, Z-scores, and statistical tests in solving real-world problems.

The analysis also shows how p-values are used to make decisions about hypotheses based on a chosen significance level.

## Author

Pallavi
