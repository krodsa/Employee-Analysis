# Employee Attrition Analysis

If GitHub fails to render the notebook, you can view the fully-rendered version here:  
https://nbviewer.org/github/krodsa/Employee-Analysis/blob/main/Employee%20Attrition%20Analysis.ipynb

Tableau dashboard can be viewed here: 
https://public.tableau.com/app/profile/krodsa/viz/EmployeeAttritionDashboard_17344953568520/AttritionDashboard

Overview

This project analyzes employee attrition trends using a dataset containing various employee attributes, including demographic details, employment history, and job satisfaction metrics. The analysis aims to identify key drivers of attrition and forecast future attrition trends for strategic workforce planning.

Objectives

1. Understand the key factors influencing employee attrition.

2. Build predictive models to classify employees likely to leave.

3. Forecast annual attrition trends for 2019, 2020, and 2021.

4. Provide actionable insights for employee retention strategies.

Project Workflow

1. Data Cleaning and Preprocessing:
- Removed missing values and duplicates to ensure data quality.
- Encoded categorical variables using LabelEncoder for machine learning compatibility.
- Standardized numerical variables using StandardScaler.

2. Exploratory Data Analysis (EDA):
- Visualized the distribution of attrition using bar plots.
- Generated a correlation heatmap to identify relationships between numerical features.

Key findings:

- JoiningYear, Age, and ExperienceInCurrentDomain were identified as significant factors affecting attrition.
- Younger employees and those with lower domain experience tend to leave more frequently.

3. Predictive Modeling: Random Forest Classifier

- Built a Random Forest Classifier to predict employee attrition (LeaveOrNot):
- Achieved high accuracy, with detailed evaluation metrics provided.
- Generated feature importance scores:
  - JoiningYear was the most significant feature, followed by Age and ExperienceInCurrentDomain.

4. Trend Forecasting: Linear Regression

- Aggregated yearly attrition counts using the JoiningYear feature.
- Used a linear regression model to forecast attrition for 2019, 2020, and 2021.

Visualizations

1. Feature Importance:

- Highlighted the top drivers of attrition, including JoiningYear, Age, and ExperienceInCurrentDomain.

2. Attrition by Key Features:

- Boxplots showing attrition trends by age and experience.
- Line plot showing attrition rates by JoiningYear.

3. Historical and Predicted Attrition Trends:

- Combined historical data and predicted attrition (2019-2021) into a single line plot for clarity.

Technologies Used

- Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- Machine Learning Models: Random Forest Classifier, Linear Regression

Results and Insights

1. Attrition Drivers:

- Younger employees and those with less experience are more likely to leave.
- Year of joining correlates strongly with attrition trends, likely reflecting changes in company policies or job market conditions.

2. Predicted Attrition forecasts for 2019, 2020, and 2021:

- 2019: [Predicted attrition value] 239
- 2020: [Predicted attrition value] 262
- 2021: [Predicted attrition value] 286

3. Retention Strategies:

- Improve onboarding for newer employees.
- Tailor retention programs to specific age groups.
- Monitor and address factors influencing attrition during certain hiring periods.



