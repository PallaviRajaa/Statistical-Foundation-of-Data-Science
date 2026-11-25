# Teaching Ratings Dataset – Data Analysis and Visualization

## Project Overview

This project uses the **Teaching Ratings Dataset** to perform data analysis and visualization using Python. The dataset contains information about professors, including their age, gender, tenure status, course division, and teaching evaluation scores.

The objective of this project is to explore the dataset, identify duplicate observations, calculate descriptive statistics, and visualize relationships between different variables.

## Dataset

The dataset used in this project is the Teaching Ratings Dataset provided by IBM Skills Network.

**Dataset URL:**  
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/teachingratings.csv

## Libraries Used

The following Python libraries are used for data analysis and visualization:

- **Pandas** – For loading, manipulating, and analyzing data.
- **NumPy** – For numerical operations.
- **Matplotlib** – For creating graphs and visualizations.
- **Seaborn** – For statistical data visualization.

## Questions and Analysis

### Question 1: Identify Duplicate Cases and Calculate Age Statistics

- Identified duplicate observations using the professor ID (`prof`).
- Calculated the average and standard deviation of age using all observations.
- Removed duplicate professor records by keeping one observation per professor.
- Recalculated the average and standard deviation of age using unique professors.

### Question 2: Average Teaching Evaluation by Course Division

- Calculated the average teaching evaluation score for each course division.
- Created a bar chart to compare evaluation scores.
- Examined whether instructors teaching lower-division courses received higher average evaluations.

### Question 3: Relationship Between Age and Teaching Evaluation

- Created a scatter plot to visualize the relationship between professors' ages and teaching evaluation scores.
- Used the plot to observe any possible trends or patterns.

### Question 4: Age and Evaluation Scores by Gender

- Created a scatter plot differentiating professors by gender.
- Compared the relationship between
