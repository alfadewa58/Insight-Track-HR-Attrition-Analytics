# HR Attrition Analytics
## By Alfa Isa Dewa

![alt text](https://github.com/alfadewa58/Bank-Instagram-Performance-Analysis/blob/main/Screenshot%202025-01-20%20172632.png)

[View the Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGIxMmY4YmMtZTg0Mi00YWVmLTk5ZGQtODQwNGJlNjU3ZDM4IiwidCI6IjUwODkxNmEwLTdiODktNDNhMS1hZjRlLTcyZmUxNWFiYTViOSIsImMiOjEwfQ%3D%3D)

## Overview
This project focuses on understanding and analyzing employee attrition in an organization. By leveraging data analytics and machine learning techniques, the goal is to identify key factors contributing to employee turnover and provide actionable insights to the HR department.

## Goals
1. Analyze patterns and trends in employee attrition.
2. Identify key factors and variables that contribute to employee turnover.
3. Develop data-driven insights to help reduce attrition rates.
4. Provide actionable recommendations for improving employee retention.

## Performed Analysis
- Plot a correlation map for all numeric variables.
- Overtime.
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

## Usage
1. Open the Jupyter Notebook file `hr_attrition_analytics.ipynb`.
2. Follow the step-by-step instructions to analyze the data and build predictive models.
3. Review the visualizations and insights provided for actionable recommendations.

## Prerequisites
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, etc.

## Installation
1. Clone this repository.
2. Install the required dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

## Results
The project delivers:
- Key drivers of employee attrition.
- A predictive model with metrics like accuracy, precision, and recall.
- Visualization of trends in employee turnover.

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

