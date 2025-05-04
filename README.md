# Employee Attrition Analysis on IBM HR Data

This project presents a detailed Exploratory Data Analysis (EDA) on IBM's HR Employee Attrition dataset using Python. The primary objective is to uncover key patterns and insights related to employee turnover through visualization and statistical techniques.

## Overview
Employee attrition is a critical concern for organizations, impacting productivity and morale. By analyzing historical HR data, we aim to identify key factors contributing to employee departures, enabling proactive retention strategies.

## Dataset
- Source: [IBM HR Employee Attrition Data](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/IBM%20HR%20Employee%20Attrition%20Data.csv)
- Records: 1,470
- Features: 35 (including both numerical and categorical variables)

## Tools & Libraries Used
- Python (Jupyter Notebook)
- Pandas
- Matplotlib
- Seaborn

## Key Analysis Steps
1. **Data Inspection:**
    - Checked dataset shape, data types, missing values, and duplicates.
    - Categorized columns into numerical and categorical features.
2. **Univariate Analysis:**
    - Visualized distributions of key numerical features like Age, Monthly Income, and Total Working Years.
    - Analyzed categorical features such as Job Role, Department, and Education Field.
3. **Bivariate Analysis:**
    - Explored relationships between features and the target variable (Attrition).
    - Created violin plots and histograms to compare distributions between employees who left and those who stayed.
4. **Correlation Analysis:**
    - Generated a heatmap to identify strong correlations between numerical features.
    - Noted significant correlations, such as between Job Level and Monthly Income.

## Insights
- **Job Level & Monthly Income:** Strong positive correlation indicates higher job levels are associated with increased income.
- **Total Working Years & Monthly Income:** Longer tenure correlates with higher income, suggesting experience impacts compensation.
- **Attrition Trends:**
      - Higher attrition observed in roles like Sales Executive and Research Scientist.
      - Departments such as Sales and R&D show increased turnover rates.
      - Educational backgrounds in Life Sciences and Medical fields have higher attrition.
  
These insights can guide HR departments in tailoring retention strategies for specific roles, departments, and educational backgrounds.

That's it! I've already added clear explanations inside the notebook itself, there shouldn't be any issues on understing the concepts. 
