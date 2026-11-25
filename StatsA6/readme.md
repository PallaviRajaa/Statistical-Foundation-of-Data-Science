# Teaching Ratings Dataset – Statistical Analysis

## Project Overview

This project uses the Teaching Ratings Dataset to perform statistical analysis using Python. The objective is to understand whether instructor characteristics such as gender, age, and tenure are related to teaching evaluation scores and beauty ratings.

The project applies three statistical tests: Independent Samples T-Test, One-Way ANOVA, and Chi-square Test of Independence.

## Dataset

The dataset used in this project is the Teaching Ratings Dataset provided by IBM Skills Network.

**Dataset URL:**

https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/teachingratings.csv

## Libraries Used

- **Pandas** – For loading and handling the dataset.
- **NumPy** – For numerical operations.
- **Matplotlib** – For data visualization.
- **Seaborn** – For statistical visualization.
- **SciPy** – For performing statistical tests.

## Questions and Analysis

### Q1. T-Test: Does Gender Affect Teaching Evaluation Rates?

An independent samples t-test was performed to compare the average teaching evaluation scores of male and female instructors.

The test determines whether there is a statistically significant difference between the evaluation scores of the two gender groups.

### Q2. ANOVA: Does Beauty Score Differ by Age?

A one-way ANOVA test was performed to examine whether instructors' beauty scores differ across age groups.

The test compares the mean beauty scores of different age groups to determine whether a statistically significant difference exists.

### Q3. Chi-square Test: Is There an Association Between Tenure and Gender?

A Chi-square test of independence was performed to determine whether tenure status is associated with gender.

A contingency table was created using gender and tenure categories, and the test was used to examine whether the two variables are statistically associated.

## Statistical Concepts Covered

- Independent Samples T-Test
- One-Way ANOVA
- Chi-square Test of Independence
- Null and Alternative Hypotheses
- P-value
- Significance Level
- Statistical Interpretation

## Tools and Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Conclusion

This project demonstrates the application of statistical tests to analyze instructor-related data. The t-test compares teaching evaluation scores by gender, ANOVA examines beauty scores across age groups, and the Chi-square test investigates the association between tenure and gender.

These methods help identify statistically significant differences and associations within the Teaching Ratings Dataset.

## Author

Pallavi
