# HR-Analytics-Dashboard-Using-Power-Bi

This project is an interactive **HR Analytics Dashboard** built in **Power BI**, designed to provide insights into employee data for better decision-making in HR departments. It covers key areas like employee demographics, attrition, satisfaction, compensation, and performance metrics.

#### Key Features:

- **Three Pages**:
  1. **Employee Overview**: Focuses on total employees, demographics (age, gender, department), and job role distribution.
  2. **Attrition & Satisfaction**: Analyzes attrition rate, satisfaction levels (job and environment), and their correlation.
  3. **Compensation & Performance**: Shows average monthly income, performance ratings, and training impact.

- **Data Source**: 
  - **HR_Analytics Dataset** (Employee information including Age, Gender, Attrition, Department, JobSatisfaction, Income, etc.).

- **Visuals**:
  - KPIs for total employees, attrition rate, and average income.
  - Bar charts for department and job role distribution.
  - Scatter plots to explore satisfaction vs. attrition and salary hike trends.

- **DAX Calculations**:
  - Used `COALESCE()` to handle missing data, ensuring that all blanks or zero values are treated as "0" for accuracy.

#### Tools Used:
- **Power BI** for data visualization.
- **DAX (Data Analysis Expressions)** to create custom metrics and handle missing data.
