# Employee Attrition Analysis on IBM HR Data

This project explores and analyzes employee attrition using IBM HR Analytics Employee Attrition & Performance dataset. The goal is to uncover patterns, identify key factors contributing to attrition, and insights related to employee turnover through visualization and statistical techniques using Python (for Data Exploration, Preprocessing, and Analyzing) and Power BI (for Interactive Report and Visual Storytelling).

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
- Power BI (power BI Desktop)
    - Power Query Editor x DAX

## Project Objectives
- Understand the key drivers of employee attrition.
- Identify roles, departments, and demographics more prone to attrition.
- Create an interactive and insightful dashboard for business stakeholders.
- Support data-driven decision-making to reduce employee turnover.

## Project Structure
- [IBM HR Employee Attrition Data.csv (Raw Data)](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/IBM%20HR%20Employee%20Attrition%20Data.csv)
- [IBM HR Employee Attrition Data.ipynb (Jupyter Notebook)](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/Dataset%203%20-%20IBM%20HR%20Employee%20Attrition%20Data.ipynb)
- [IBM HR Employee Attrition Analysis.pbix (Power BI Report)](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/IBM%20HR%20Employee%20Attrition%20Analysis.pbix)
- [IBM HR Employee Attrition Report.pdf (Power BI Report - PDF)](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/IBM%20HR%20Employee%20Attrition%20Report.pdf)
- [IBM_HR_EDA_Report.html (EDA Report)](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/IBM_HR_EDA_Report.html)
- [README.md](https://github.com/nibeditans/Employee-Attrition-Analysis-On-IBM-HR-Data/blob/main/README.md)


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

## 📬 Contact
Feel free to connect if you'd like to discuss this project or have any feedback!
- GitHub: [@nibeditans](https://github.com/nibeditans)
- LinkedIn: [Nibedita Sahu](https://in.linkedin.com/in/ns-nibedita-sahu)
