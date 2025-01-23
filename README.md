# HR Attrition Analytics
## By Alfa Isa Dewa

![Dashboard Preview](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/Screenshot%202025-01-21%20183226.png)

[View the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGIxMmY4YmMtZTg0Mi00YWVmLTk5ZGQtODQwNGJlNjU3ZDM4IiwidCI6IjUwODkxNmEwLTdiODktNDNhMS1hZjRlLTcyZmUxNWFiYTViOSIsImMiOjEwfQ%3D%3D)

## Overview
This project focuses on understanding and analyzing employee attrition in an organization. By leveraging data analytics, the goal is to identify key factors contributing to employee turnover and provide actionable insights to the HR department.

## Goals
1. Analyze patterns and trends in employee attrition.
2. Identify key factors and variables that contribute to employee turnover.
3. Develop data-driven insights to help reduce attrition rates.
4. Provide actionable recommendations for improving employee retention.

## Performed Analysis
### 1. Plot a correlation map for all numeric variables.
![alt text](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/heatmap.png)
Insights:
**Strong Correlations:**
- Job Level and Monthly Income (0.95): 
    + Employees in higher job levels are paid substantially more than those in lower levels.
- Years at Company and Years with Current Manager (0.77): 
    + Employees who stay longer at a company are likely to have worked longer with their current manager.
- Total Working Years and Job Level (0.78): 
    + Which suggests that as employees gain more work experience, they are likely to attain higher job levels.
- Total Working Years and Monthly Income (0.77): 
    + Showing that employees with more experience tend to earn higher monthly incomes.

### 2. Attrition by Overtime.
![AttrbyOvertime](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/Screenshot%202025-01-23%20123656.png)

**Insights:**
- Total employees working overtime: 416 out of 1,470 employees (approximately 28.3%) are working overtime. This indicates that a significant portion of the workforce is engaged in overtime, which could suggest **high workloads or a culture of extended working hours.**
- Attrition among overtime employees: 30.5% of employees who work overtime have left the company. This is notably high and suggests that overtime work may be a contributing factor to employee **dissatisfaction or burnout.**
- Attrition among non-overtime employees: In contrast, only 10.4% of employees who do not work overtime have left the company. This indicates a much lower turnover rate among those who maintain a **standard work schedule.**



### 3. Marital Status.
![AttrbyOvertime](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/3.%20Attr%20Rates%20by%20Marital%20Status.png)

**Insights:**
Single employees have the highest attrition rate (25.5%), while divorced employees have the lowest (10.1%). Married employees show moderate stability (12.5%).

### 4. Job Role.
![AttrbyOvertime](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/Screenshot%202025-01-23%20134551.png)

**Insights:**
+ Sales Representatives and Laboratory Technicians show high turnover rates, indicating potential dissatisfaction or stress in these roles.
+ Research Directors and Managers have low attrition, suggesting higher satisfaction and job security.

### 5. Education Field.
![AttrbyEdField](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/12%20-%20Attr%20by%20Ed%20Field.png)

**Insights:**
+ Conversely, employees in Life Sciences and Medical fields show lower attrition rates, suggesting that these roles may offer more job satisfaction or stability.

### 6. Department.
![AttrbyDepartment](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/5%20-%20Attr%20Rates%20by%20Department.png)

**Insights:**
- Research & Development is the largest department, comprising approximately 65% of the workforce, followed by Sales (~30%) and Human Resources (~5%)
- Sales department shows the highest attrition rate at around 20%, significantly higher than other departments
- Human Resources has a moderate attrition rate of approximately 15%

### 7. Business Travel.
![AttrbyBusinessTravel](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/6%20-%20Attr%20Rates%20by%20Business%20Travel.png)

**Insights:**
- Travel Rarely: The attrition rate is 15.0%. This indicates a moderate level of turnover among employees who travel infrequently, suggesting that while they are relatively stable, there is still a notable risk of losing these employees.
- Travel Frequently: The attrition rate is 24.9%, which is significantly higher than that of employees who travel rarely. This suggests that frequent travelers may experience higher levels of stress, work-life imbalance, or job dissatisfaction, leading to a greater likelihood of leaving the organization.
- Non-Travel: The attrition rate is 8.0%, which is the lowest among the three categories. This indicates that employees who do not travel for work are the most stable group, possibly due to fewer job-related stresses associated with travel.

### 8. Number of Companies Worked.
![AttrbyNumCompWorked](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/10%20-%20Attr%20Rates%20by%20Companies%20Worked.png)

**Insights:**
- Moderate Stability for Fewer Job Changes: Employees with 0, 2, or 3 previous companies show lower attrition rates, indicating that those with fewer job changes may be more stable and satisfied in their current roles.
- Potential for Job Hopping: The higher attrition rates among employees with one previous job and those with multiple job changes suggest a potential trend of job hopping, which may be influenced by factors such as career advancement opportunities, job satisfaction, or work-life balance.

### 9. Distance from Home.
![AttrbyDistFromHome](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/11%20-%20Attr%20Rates%20by%20Dist%20From%20Home.png)

**Insights:**
- Potential for Increased Turnover: The higher attrition rates for employees living 11 miles or more from the workplace highlight the need for organizations to consider the impact of commuting on employee retention. Long commutes can lead to increased stress and reduced work-life balance.

### 10. Relation between Overtime and Age.
![CorrOvertimeVsAge](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/7%20-%20Corr%20Age%20vs%20Overtime.png)

**No Significant Age Impact:** The analysis suggests that age does not significantly influence whether employees work overtime. This could imply that factors other than age, such as job role, workload, or personal circumstances, may play a more critical role in determining overtime work.

### 11. Relation of Total Working Years vs Overtime.
![CorrOvertimeVsTotWorkingYears](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/8%20-%20Corr%20Total%20Working%20Years%20vs%20Overtime.png)

The data indicates that Total Working Years **does not have a significant correlation** with Overtime, suggesting that an employee's overall career duration has little impact on their likelihood to work overtime.

### 12. Relation of Education Level vs Attrition.
![CorrEdLevelVsAttrition](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/assets/9%20-%20Corr%20Education%20Status%20vs%20Attrition.png)

The analysis suggests that **education level does not significantly influence attrition rates**. Employees across different education levels exhibit similar turnover patterns, indicating that factors other than education may be more critical in determining attrition.

## Stakeholders
- HR Department
- Senior Management


## Conclusions (Shortened)
**Strong Correlations**
- Job Level and Monthly Income: Higher job levels correspond to significantly higher salaries.
- Years at Company and Years with Current Manager: Long-tenured employees tend to work under the same manager for extended periods.
- Total Working Years and Monthly Income: More experienced employees earn higher salaries.

**Moderate Correlations**
- Age and Total Working Years: Older employees generally have more work experience.
- Years Since Last Promotion and Years in Current Role: Lack of promotions often coincides with employees remaining in the same role.

**Attrition Insights**
- Overtime: Employees working overtime face higher attrition rates.
- Marital Status: Single employees exhibit the highest attrition rates.
- Role-Specific Insights: Sales Representatives and Laboratory Technicians show high turnover.
- Education and Department: Attrition is higher among employees with Marketing and Technical backgrounds, while Research & Development shows lower turnover.

**Statistical Findings**
- Education Level and Attrition: No significant impact of education level on attrition.
- Age and Overtime: No statistically significant relationship.


## Recommendations:  

1. **Career Development**:  
   - Implement a structured career advancement program that includes biannual performance reviews and clear promotion criteria.  
   - Provide a mentorship program targeting employees with over five years of tenure, aiming for at least a 20% increase in internal promotions within the next 12 months.  
   - Allocate budgets for training and certifications, offering a minimum of two learning opportunities annually for each long-tenured employee.  

2. **Workload and Overtime**:  
   - Cap overtime hours to a maximum of 10 hours per month per employee.  
   - Implement team-based workload balancing to reduce reliance on overtime by 25% within six months.  
   - Introduce quarterly employee well-being surveys to monitor burnout levels, targeting a 15% reduction in negative responses by year-end.  

3. **Targeted Retention Programs**:  
   - Focus on high-turnover roles such as Sales Representatives by introducing incentive programs, such as quarterly bonuses for achieving 90% of sales targets, to reduce attrition by 10% in this group.  
   - Offer tailored benefits for single employees, such as subsidized gym memberships or social activities, and provide travel flexibility (e.g., fewer mandatory trips) to reduce turnover among frequent travelers by 15%.  

4. **Support for Long Commutes**:  
   - Offer flexible schedules, allowing employees with commutes over 60 minutes to work at least two days remotely per week.  
   - Provide a transportation allowance of $100 per month for employees commuting more than 30 miles to offset costs and improve morale.  
   - Aim to increase satisfaction scores for employees with long commutes by 20% through these measures within the next year.  

