# HR-Attrition-Dashboard

#Project Overview
This project analyzes employee attrition trends using the HR dataset from Kaggle to identify key insights that can help the organization improve employee retention. Power BI was used for data visualization and analysis.

#Steps of the Process:
Data Collection:

Downloaded the HR dataset from Kaggle, which includes data on employees' job roles, experience, salary, age, performance, and other factors affecting attrition.
Data Loading:

Loaded the dataset into Power BI for further processing and analysis.
Data Cleaning:

Removed duplicate records.
Handled missing values through imputation and removal, depending on the severity and distribution of missing data.
Performed data normalization to ensure consistency in values.
Data Transformation:

Created new calculated columns:
Age Group: Segmented employees into various age groups (e.g., 18-25, 25-35, 35-45, etc.) to analyze attrition across different demographics.
DAX Measures:

Created custom DAX measures for essential metrics:
Attrition Rate: (Number of employees left / Total number of employees) * 100
Average Salary: Calculated the average salary for employees in each job role and across departments.
Visualization:

Developed interactive dashboards with the following visualizations:
Pie Charts: To show attrition distribution across different categories like job role, gender, and salary.
Bar Graphs: To compare attrition rates by job role, department, and experience.
Area Charts: To track trends over time for employee retention and attrition.

##Top Insights:
Job Role:
The Sales and Marketing teams have the highest attrition rate compared to other departments, indicating a possible issue with job satisfaction or career growth opportunities in these areas.

Experience:
Employees with 2 to 5 years of experience exhibit the highest likelihood of leaving the company, suggesting that this group might feel stagnated or seek new challenges elsewhere.

Age Group:
The 25-35 age group has the highest turnover rate, which may indicate a shift in priorities or career goals at this stage of life. This group might be looking for better work-life balance or more senior roles.
Salary:

Employees earning less than $50,000 are more likely to leave the company, which suggests a correlation between lower salaries and higher turnover, potentially due to dissatisfaction with compensation.

##Conclusion:
This analysis provides valuable insights into employee attrition trends and highlights key factors that could be addressed to improve retention. The interactive dashboard in Power BI allows HR teams to monitor these metrics regularly and implement data-driven strategies for retaining employees.
