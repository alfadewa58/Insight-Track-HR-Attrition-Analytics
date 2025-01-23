# HR Attrition Analytics
## By Alfa Isa Dewa

![alt text](https://github.com/alfadewa58/Insight-Track-HR-Attrition-Analytics/blob/main/Screenshot%202025-01-21%20183226.png)

[View the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGIxMmY4YmMtZTg0Mi00YWVmLTk5ZGQtODQwNGJlNjU3ZDM4IiwidCI6IjUwODkxNmEwLTdiODktNDNhMS1hZjRlLTcyZmUxNWFiYTViOSIsImMiOjEwfQ%3D%3D)

## - Overview
This project focuses on understanding and analyzing employee attrition in an organization. By leveraging data analytics, the goal is to identify key factors contributing to employee turnover and provide actionable insights to the HR department.

## Goals
1. Analyze patterns and trends in employee attrition.
2. Identify key factors and variables that contribute to employee turnover.
3. Develop data-driven insights to help reduce attrition rates.
4. Provide actionable recommendations for improving employee retention.

## Performed Analysis
### Plot a correlation map for all numeric variables.
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
### Overtime.

Insights:
- Marital Status.
- Job Role.
- Gender.
- Education Field.
- Department.
- Business Travel.
- Relation between Overtime and Age.
- Total Working Years.
- Education Level.
- Number of Companies Worked.
- Distance from Home.

## Stakeholders
- HR Department
- Senior Management

## Installation
1. Clone this repository.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

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

## Recommendations
- **Career Development**: Address promotion gaps and career stagnation for long-tenured employees by creating clear pathways for advancement.
- **Workload and Overtime**: Reduce reliance on overtime to mitigate burnout and support employee well-being.
- **Targeted Retention Programs**: Focus on high-turnover roles (e.g., Sales Representatives) and groups (e.g., single employees, frequent travelers) with tailored strategies to improve engagement and retention.
- **Support for Long Commutes**: Offer flexible schedules or remote work options to employees with lengthy commutes to enhance work-life balance.

