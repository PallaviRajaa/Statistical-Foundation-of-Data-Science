# TeachingRatings Dataset – Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the **TeachingRatings dataset** using Python.

The dataset contains information about university instructors and their teaching evaluations. The analysis focuses on understanding the dataset, examining student-related statistics, visualizing beauty scores, and exploring differences between male and female instructors.

The main objective of this project is to understand how Python libraries can be used to analyze real-world data and extract meaningful insights.

## Dataset

The TeachingRatings dataset is obtained from the AER package and is available through the Rdatasets repository.

**Dataset URL:**  
https://raw.githubusercontent.com/vincentarelbundock/Rdatasets/master/csv/AER/TeachingRatings.csv

The dataset contains information about instructors, including:

- Gender
- Beauty score
- Teaching evaluation
- Number of students
- Tenure status

The dataset represents **cross-sectional data**, as it contains observations of different instructors and courses rather than measurements collected over time.

## Tools and Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Analysis Performed

### 1. Data Loading and Inspection
- Imported the required Python libraries.
- Loaded the dataset using `pandas.read_csv()`.
- Displayed the first five rows using `df.head()`.
- Checked the number of rows and columns.
- Displayed the column names.

### 2. Data Classification
Identified the dataset as cross-sectional data based on the nature of its observations.

### 3. Statistical Analysis
Calculated the following descriptive statistics for the number of students:

- Mean
- Median
- Minimum
- Maximum

### 4. Descriptive Analysis
Used `df.describe()` to obtain a statistical summary of the numerical variables in the dataset.

### 5. Data Visualization
Created a histogram of the beauty variable using Matplotlib to understand the distribution of beauty scores among instructors.

### 6. Gender Analysis
- Counted the number of male and female instructors.
- Calculated the mean, standard deviation, and count of beauty scores for each gender.
- Compared the average beauty scores between male and female instructors.

### 7. Tenure Analysis
Calculated the percentage of male and female instructors who have tenure.

## Key Findings

- The dataset contains observations of different instructors and courses.
- Female instructors have a higher average beauty score than male instructors in this sample.
- The variation in beauty scores is relatively similar across both gender groups.
- The dataset contains more male instructors than female instructors.
- A higher percentage of male instructors are tenured compared to female instructors.
- The histogram helps visualize the distribution and variation of beauty scores.

## Conclusion

This project demonstrates the use of Python for basic data analysis and visualization.

Through Pandas, NumPy, and Matplotlib, the dataset was explored using descriptive statistics, grouping, aggregation, and graphical representation.

The analysis helped identify patterns in beauty scores, gender distribution, and tenure percentages. This project provides a foundation for further statistical analysis and hypothesis testing.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib
   ```

3. Open the Python notebook or script.
4. Run the code cells sequentially.
5. The dataset will be loaded directly from the provided URL.

## Author

Pallavi

**Project Type:** Data Science – Exploratory Data Analysis (EDA)
