# EDA-Project-1Analysis-of-AMCAT-Data

This project involves Exploratory Data Analysis (EDA) on a dataset from AMCAT to uncover insights related to employee salaries, experience, and other key factors. The goal is to understand trends, patterns, and relationships within the data, and address questions related to salary distribution, employee attrition, and gender-based salary comparisons.

Key Objectives
Identify the highest salary of employees who left the company and analyze their experience.
Investigate the "Open_Experience" of employees with high salaries who left the company.
Count the number of employees still working and determine how many earn more than the average salary.
Compare the average salary of male and female employees to uncover any gender salary gaps.
Use univariate analysis to explore the distribution of salary and other important features in the dataset.
Methods and Tools
Python: The primary programming language used for analysis.
Pandas: For data manipulation and handling missing values.
Matplotlib/Seaborn: For data visualization and generating insights from histograms and box plots.
Descriptive Statistics: Used to generate summary statistics with df.describe().
Interquartile Range (IQR): Applied to detect outliers in the dataset.
df.info(): Used to examine data types and identify missing values in columns.
Steps Performed
Data Cleaning: Checked for missing values and cleaned the dataset accordingly.
Univariate Analysis: Focused on analyzing the "Salary" column to understand its distribution and detect outliers.
Outlier Detection: Used IQR to identify outliers in salary data.
Descriptive Statistics: Generated summary statistics using df.describe().
Gender Salary Comparison: Calculated and compared the average salaries of male and female employees.
Employee Attrition Analysis: Analyzed the highest salary and experience of employees who left the company.
Key Insights
The highest salary of an employee who left the company is 4,000,000.
The "Open_Experience" of employees with high salaries who left the company is found to be -0.1295 and -2.6572.
There are 1,095 employees still working, and the majority of them earn more than the average salary.
A gender-based salary gap is observed, with male employees earning slightly more on average than female employees.
Future Work
Explore bivariate and multivariate analyses to uncover deeper relationships between variables.
Use machine learning models to predict employee attrition based on salary, experience, and other factors.
Investigate the impact of other features like education level, job role, and location on salary and employee retention.
