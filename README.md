# HR Data Analysis Using MySQL Employee Satisfaction and Attrition Insights

## Project Overview

This project focuses on analyzing HR data stored in a MySQL database to uncover insights into employee satisfaction, attrition rates, and workforce trends. By querying and aggregating data based on various employee attributes such as age, department, education, and marital status, this project provides valuable insights that can help HR teams optimize employee engagement, retention, and departmental performance.

The analysis is performed using SQL queries to answer critical questions that guide HR decision-making and improve employee experience.

### Key Objectives:
- Explore patterns of employee satisfaction across departments and roles.
- Identify employee demographics that correlate with higher attrition rates.
- Understand the relationship between job satisfaction and factors such as education, marital status, and business travel.

## Dataset

The dataset used in this project includes various attributes of employees that provide detailed insights into employee demographics and their job satisfaction levels. Key columns in the dataset are:

- **Age**: The age of the employee.
- **Department**: The department the employee belongs to.
- **Job Role**: The specific job role or title of the employee.
- **Job Satisfaction**: Rating of the employee's satisfaction (scale from 1 to 5).
- **Attrition**: Whether the employee has left the company ("Yes" or "No").
- **Education**: The education level of the employee.
- **Marital Status**: The marital status of the employee (e.g., "Single", "Married").
- **Business Travel**: Whether the employee travels frequently for business ("Travel_Frequently" or "Non-Travel").

The dataset is stored in a MySQL database in a table called `hrdata`.

## Analysis

The analysis performed in this project answers several key HR-related questions, which can help HR teams make data-driven decisions:

### 1. **Employee Distribution by Department**
   - **Query**: Count the number of employees in each department.
   - **Insight**: Understand the staffing level in each department to identify any overstaffing or understaffing.

### 2. **Average Age by Department**
   - **Query**: Calculate the average age of employees in each department.
   - **Insight**: Assess the age distribution across departments to identify trends in workforce demographics.

### 3. **Most Common Job Roles by Department**
   - **Query**: Identify the most common job roles within each department.
   - **Insight**: Determine the distribution of job roles within departments and identify potential gaps or over-representation.

### 4. **Job Satisfaction by Education Level**
   - **Query**: Calculate the average job satisfaction for each education level.
   - **Insight**: Determine whether employees with higher education levels report higher job satisfaction.

### 5. **Average Age by Job Satisfaction**
   - **Query**: Determine the average age for employees with different levels of job satisfaction.
   - **Insight**: Understand how age influences job satisfaction levels.

### 6. **Attrition Rate by Age Band**
   - **Query**: Calculate the attrition rate for each age band.
   - **Insight**: Identify which age groups have higher attrition rates, enabling targeted retention strategies.

### 7. **Department with Highest and Lowest Job Satisfaction**
   - **Query**: Identify the departments with the highest and lowest average job satisfaction.
   - **Insight**: Focus on departments with lower job satisfaction and explore ways to improve engagement.

### 8. **Attrition Rate by Education Level and Age Band**
   - **Query**: Find the age band with the highest attrition rate among employees with a specific education level.
   - **Insight**: Target high-risk age and education demographic groups with retention efforts.

### 9. **Job Satisfaction by Business Travel Frequency**
   - **Query**: Find the education level with the highest average job satisfaction among employees who travel frequently.
   - **Insight**: Understand if business travel negatively impacts job satisfaction and if specific education levels perform better under such conditions.

### 10. **Job Satisfaction by Marital Status**
   - **Query**: Identify the age band with the highest average job satisfaction among married employees.
   - **Insight**: Assess the impact of marital status on job satisfaction and engagement.

### 11. **Job Satisfaction by Role**
   - **Query**: Calculate job satisfaction by role.
   - **Insight**: Analyze if certain roles have consistently higher or lower job satisfaction.

### 12. **Attrition Rate by Business Travel Status**
   - **Query**: Calculate the attrition rate based on business travel frequency.
   - **Insight**: Assess the relationship between business travel and attrition, highlighting potential risk factors.

### 13. **Job Satisfaction vs. Attrition**
   - **Query**: Explore job satisfaction levels vs attrition rates.
   - **Insight**: Investigate how lower satisfaction levels correlate with higher attrition.

### 14. **Job Satisfaction by Marital Status**
   - **Query**: Analyze job satisfaction based on marital status.
   - **Insight**: Explore the relationship between job satisfaction and employees' marital status.

### 15. **Attrition Rate by Job Role and Age Band**
   - **Query**: Calculate the attrition rate by job role and age band.
   - **Insight**: Identify which job roles and age groups experience higher attrition rates and devise specific retention strategies.

## Conclusion

The HR data analysis provides several key insights:

- **Employee Distribution**: Some departments are overstaffed or understaffed, providing opportunities for better workforce planning.
- **Job Satisfaction**: Employees with higher education tend to report higher job satisfaction. Additionally, job satisfaction varies with factors like marital status, business travel, and age.
- **Attrition Rates**: Younger employees, especially in specific age bands, experience higher attrition rates. Job roles and departments also play a role in attrition trends.
- **Targeted Interventions**: The analysis suggests that HR can improve employee satisfaction and retention by focusing on specific departments, job roles, and demographics.

This analysis will help HR departments optimize workforce planning, retention strategies, and employee engagement efforts.

