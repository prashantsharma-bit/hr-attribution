HR Employee Attrition Analysis
Project Overview
This project performs an exploratory data analysis (EDA) on the HR Employee Attrition dataset to identify key factors influencing employee turnover. The analysis aims to uncover patterns and insights that can help organizations understand why employees leave and what factors contribute to employee retention.

Dataset Description
The dataset contains 1,470 employee records with 35 features related to employee demographics, job satisfaction, compensation, work environment, and career progression. The target variable is Attrition, indicating whether an employee has left the company (Yes/No).

Key Features:
Demographics: Age, Gender, Marital Status, DistanceFromHome

Job-related: Department, JobRole, JobLevel, JobSatisfaction, OverTime

Compensation: MonthlyIncome, HourlyRate, DailyRate, PercentSalaryHike

Experience: YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, TotalWorkingYears

Work Environment: EnvironmentSatisfaction, RelationshipSatisfaction, WorkLifeBalance

Other: BusinessTravel, Education, StockOptionLevel, PerformanceRating

Analysis Summary
1. Data Quality Assessment
No missing values found in the dataset

No duplicate records detected

Dataset is clean and ready for analysis

2. Key Metrics
Total Employees: 1,470

Overall Attrition Rate: 16.12%

Average Monthly Income: $6,502.93

3. Department-wise Analysis
Research & Development: 961 employees (65.37%)

Sales: 446 employees (30.34%)

Human Resources: 63 employees (4.29%)

Attrition by Department:
Department	Attrition Rate
Sales	~20.6%
HR	~19.0%
R&D	~13.8%
4. Gender Distribution
Male: 882 employees (60%)

Female: 588 employees (40%)

Slightly higher attrition rate observed among male employees (17.0%) compared to females (14.8%)

5. Key Insights
a. Overtime Impact
Employees working overtime show significantly higher attrition rates

Overtime is a major predictor of employee turnover

b. Age Factor
Younger employees (20-30 age group) show higher attrition

Older, more experienced employees tend to stay longer

c. Income Correlation
Employees with lower monthly income have higher attrition rates

Salary appears to be a significant retention factor

d. Job Satisfaction
Lower job satisfaction correlates with higher attrition

Employees who left rated their job satisfaction lower on average

e. Department Risk
Sales department has the highest attrition rate

R&D department shows the lowest attrition

6. Correlation Analysis
The correlation heatmap reveals:

Positive correlations: MonthlyIncome with JobLevel and TotalWorkingYears

Negative correlations: Attrition with JobSatisfaction and WorkLifeBalance

Weak correlation between PerformanceRating and Attrition

Visualizations
Charts Included:
Pie Chart: Overall Attrition Distribution

Bar Charts:

Attrition by Department

Attrition by Gender

Attrition by Overtime Status

Histogram: Age Distribution by Attrition Status

Box Plot: Monthly Income Distribution by Attrition

Count Plot: Job Satisfaction vs Attrition

Heatmap: Correlation Matrix of Numeric Features

Key Findings
Department Risk: Sales department faces the highest attrition risk

Overtime Impact: Overtime is strongly associated with higher turnover

Younger Workforce Vulnerability: Younger employees are more likely to leave

Compensation Matters: Lower income correlates with higher attrition

Job Satisfaction Critical: Dissatisfied employees are more likely to quit

Work-Life Balance Important: Better work-life balance leads to lower attrition

Recommendations
Review Overtime Policies: Investigate departments with high overtime and consider workload redistribution

Compensation Review: Benchmark salaries, especially for entry-level and junior positions

Career Development: Focus on retention programs for younger employees

Department Interventions: Target Sales department with additional retention strategies

Work-Life Balance Programs: Implement flexible working arrangements

Employee Engagement: Regular surveys to monitor job satisfaction trends

Files in Repository
HR Employee Attrition.csv: Original dataset

hr_cleaned.csv: Cleaned dataset (after initial preprocessing)

hr.ipynb: Jupyter notebook containing the complete analysis code

README.md: Project documentation (this file)

Requirements
text
pandas
numpy
matplotlib
seaborn
How to Run the Analysis
Clone the repository

Install required packages: pip install -r requirements.txt

Open the Jupyter notebook: jupyter notebook hr.ipynb

Run all cells to reproduce the analysis

Conclusion
The analysis provides actionable insights into employee attrition patterns. Key drivers include overtime, compensation, job satisfaction, and department. Organizations can use these insights to develop targeted retention strategies and reduce voluntary turnover.

Future Work
Build predictive models for attrition (Logistic Regression, Random Forest, XGBoost)

Feature importance analysis to identify most influential predictors

Time-series analysis of attrition trends over time

Employee sentiment analysis from feedback surveys

