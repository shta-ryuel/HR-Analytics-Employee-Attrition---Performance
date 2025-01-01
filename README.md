# HR Analytics Employee Attrition & Performance

This project analyzes the IBM HR Analytics Employee Attrition & Performance dataset to uncover patterns in employee behavior, performance, and attrition. It includes detailed data cleaning, exploratory data analysis (EDA), and interactive visualizations to provide actionable insights for HR decision-making.

## Project Overview

- **Objective**: To analyze employee attrition, performance metrics, and identify factors contributing to employee retention.
- **Dataset**: IBM HR Analytics Employee Attrition & Performance dataset containing 35 columns.
  Link to original dataset: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset 

## Key Questions Addressed

1. What factors contribute most to employee attrition?
2. How does job satisfaction vary across departments and roles?
3. What is the relationship between performance and tenure?
4. Are there patterns in attrition based on demographic or job-level data?

## Technologies Used

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Visualization Tool**: Tableau

## Features

- Data cleaning and preprocessing to handle missing values and categorical data.
- Statistical analysis and visualizations of key metrics such as attrition rate, job satisfaction, and performance ratings.
- Creation of an interactive Tableau dashboard to showcase insights.

## File Structure

```
HR_Analytics/
├── data/
│   ├── HR-Employee-Attrition.csv  # Original dataset
├── notebooks/
│   ├── main.ipynb                 # Main notebook for analysis
├── visualizations/
│   ├── tableau_dashboard.twbx     # Tableau dashboard file
├── README.md                      # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/HR_Analytics.git
   cd HR_Analytics
   ```
2. Run the analysis:
   ```bash
   jupyter notebook notebooks/main.ipynb
   ```

## Tableau Dashboard

The interactive dashboard provides:
- Attrition trends across departments and roles.
- Visualizations of performance ratings and job satisfaction.
- Insights into demographic patterns and their effect on attrition.

## Insights

1. **Attrition Analysis**: Key factors like job role, satisfaction, and work-life balance significantly impact attrition.
2. **Job Satisfaction**: Higher satisfaction correlates with better performance and retention.
3. **Performance Trends**: Employees with longer tenure and consistent training tend to perform better.

## Conclusion

This project provides a comprehensive analysis of employee attrition and performance metrics. By leveraging Python and Tableau, actionable insights were derived to support HR strategies for improving retention and satisfaction.

