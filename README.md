# hr-analytics-dashboard
AI-driven HR Analytics Dashboard and Decision Support System
# HR Analytics Dashboard for Decision Support
## Problem Statement

Organizations often face challenges in managing employee performance and reducing attrition due to the lack of real-time insights and structured decision-making systems. HR teams rely on scattered data sources such as attendance records, satisfaction scores, and performance metrics, which makes it difficult to identify at-risk employees and take timely action.

The absence of an integrated system leads to delayed decisions, increased employee turnover, and reduced organizational efficiency.

This project aims to solve this problem by developing an AI-driven HR Analytics Dashboard and Decision Support System that provides clear insights, identifies high-risk employees, and recommends actionable strategies to improve employee retention and performance.
## Dashboard Preview
<img width="1740" height="800" alt="Screenshot 2026-04-08 192356" src="https://github.com/user-attachments/assets/327eebd9-9eb3-420b-973b-f46733879e59" />


## Project Overview
This project demonstrates how data analytics and AI-based logic can be used to solve real-world HR problems. It combines data analysis, dashboard visualization, and a decision support system.

## Business Objective
- Monitor employee performance
- Identify attrition trends
- Support HR decision-making
- Improve workforce management

## Business Flow
Data → Analysis → Dashboard → Decision → Action

## Dataset Features
- employee_id
- department
- satisfaction_score
- attendance_percent
- performance_rating
- overtime_hours
- attrition
- recruitment_source

## Dashboard Description
The dashboard provides a clear view of employee insights:



### KPIs
- Total Employees
- Average Satisfaction Score
- Average Attendance
- Attrition Count
- Average Performance Rating

### Visuals
- Attrition by Department
- Satisfaction by Department
- Overtime vs Attrition
- Performance Distribution
- Recruitment Source Breakdown

### Filters
- Department
- Gender
- Attrition
- Recruitment Source

## Decision Support System
A rule-based DSS is implemented to support HR decisions.

### Risk Classification
- High Risk: Low satisfaction + high overtime
- Medium Risk: Low satisfaction or low attendance
- Low Risk: Stable employees

### Recommendations
- High Risk: Immediate intervention
- Medium Risk: Monitor and engage
- Low Risk: Maintain performance

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Power BI

## Project Structure
hr-analytics-dashboard/
 ├── data
 ├── dashboard
 ├── notebooks
 ├── src
 ├── README.md
 └── requirements.txt

## How to Run
1. Open notebook in Google Colab
2. Run all cells
3. View charts and insights

## Business Insights
- High attrition departments need attention
- Overtime contributes to employee burnout
- Low satisfaction indicates engagement issues
- Recruitment source impacts performance

## Conclusion
This project shows how data can be transformed into insights and decisions using AI-driven logic and dashboards.


