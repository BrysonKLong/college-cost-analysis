# College Cost Analysis & Predictive Modeling

## Overview

This project analyzes data from 777 U.S. colleges to identify the factors that influence college attendance costs and predict tuition using multiple linear regression.

## Business Problem

College affordability is an important issue for students and families. This project investigates which institutional characteristics contribute most to higher costs.

## Dataset

- 777 U.S. colleges
- Public and Private Institutions

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels

## Key Findings

- Private colleges cost approximately $5,356 more than public colleges.
- Private institutions spend roughly $3,028 more per student.
- Regression model explained approximately 50% of tuition variation.

## Visualizations

### Relationship Between Expenditure and College Cost

![Relationship Between Expenditure and College Cost](images/expenditure_vs_cost.png)

This scatter plot illustrates the positive relationship between institutional expenditure per student and the overall cost of attendance. Colleges with higher spending per student generally have higher attendance costs.

---

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

The correlation matrix highlights the strength of relationships among numerical variables. It helped identify which features were most strongly associated with college costs before developing the predictive model.

---

### College Cost Distribution

![College Cost Distribution](images/college_cost_distribution.png)

The distribution of attendance costs across 777 U.S. colleges shows substantial variation between institutions, emphasizing the complexity of predicting tuition and overall costs.

---

### Regression Diagnostics

![Regression Diagnostics](images/regression_diagnostics.png)

Regression diagnostic plots were used to evaluate model assumptions, including residual behavior and overall model fit, ensuring the validity of the multiple linear regression model.

## Repository Contents

- CollegeCostAnalysis.ipynb
- README.md

## Future Improvements

- Compare additional machine learning models
- Expand feature engineering
- Create interactive dashboards
