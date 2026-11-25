TeachingRatings Dataset Analysis
Project Overview
This project uses the TeachingRatings dataset to explore information about professors, including their age, gender, tenure status, minority status, and teaching evaluation scores.

The analysis is performed using Python and the libraries Pandas and Matplotlib. It includes basic data exploration, percentage calculation, summary statistics, and visualizations.
Dataset
The dataset is loaded directly from the IBM Skills Network course resource:
url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ST0151EN-SkillsNetwork/labs/teachingratings.csv"
The dataset contains information about professors and their teaching ratings.
Libraries Used
- Pandas – Used to load, organize, group, and analyze the dataset.
- Matplotlib – Used to create graphs and visualize the data.
Analysis Performed
1. Percentage of Visible Minority Professors
The dataset is grouped by the minority variable, and the percentage of professors in each group is calculated.

Finding: Approximately 13.82% of the professors are visible minorities, while 86.18% are non-minorities.
2. Average Age by Tenure
The mean and standard deviation of professors' ages are calculated for each tenure group.

Finding: The average age differs between the tenure groups. The reported average age is approximately 50.19 years for untenured professors and 47.85 years for tenured professors.
3. Age Distribution
A histogram is created to show the distribution of professors' ages.

A histogram is appropriate because age is a numerical variable. It helps identify how frequently ages occur across different intervals.
4. Gender Distribution
Two bar charts are created using:
- pyplot.bar() – Displays categories using vertical bars.
- pyplot.barh() – Displays categories using horizontal bars.
Bar charts are suitable for gender because it is a categorical variable.
5. Median Evaluation Score of Tenured Professors
The median teaching evaluation score is calculated for professors whose tenure value is "yes".

The exact median is displayed by the Python code.
How to Run the Project
1. Make sure Python is installed.
2. Install the required libraries:
   pip install pandas matplotlib
3. Open the Python notebook or script containing the analysis.
4. Run the code cells in order.
5. The dataset will be loaded from the URL, and the analysis and graphs will be displayed.
Conclusion
This project demonstrates how Pandas can be used to analyze categorical and numerical data, calculate percentages and summary statistics, and how Matplotlib can be used to visualize data using histograms and bar charts.

It provides a basic understanding of exploratory data analysis (EDA) using a real-world educational dataset.
