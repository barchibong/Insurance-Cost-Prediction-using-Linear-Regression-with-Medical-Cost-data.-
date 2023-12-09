
This project utilizes a dataset sourced from Kaggle, containing medical costs personal datasets in JSON format. The dataset comprises columns such as age, BMI, children, smoker status, charges, sex, and region. The primary objective is to predict insurance costs through linear regression analysis.

Research Questions:
1. What is the relationship between Age and Charges? Are older individuals more likely to incur higher medical charges compared to younger individuals?
2. Is there a correlation between BMI and medical costs? Do individuals with higher BMI tend to have elevated medical charges compared to those with lower BMI?

Variables:
- Dependent Variable: Charges
- Independent Variables: Age, BMI

Findings:
The correlation coefficient between charge and age is 0.3, indicating a moderate positive correlation. This suggests that older individuals tend to have higher medical charges compared to younger ones (Research Hypothesis 1).

The correlation coefficient between charge and BMI is 0.2, representing a weak positive correlation. This implies that higher BMI is positively associated with increased medical charges (Research Hypothesis 2).

Tools and Libraries Used:
- Python Jupyter notebook
- Libraries: Pandas, NumPy, os, Matplotlib, Seaborn, SciPy, Folium.

Data Processing:
The data underwent cleaning and wrangling processes, including checks for duplicates, handling missing values, column renaming, and creating subsets.

Visualizations:
Visualizations such as correlation heat maps, scatterplots, pair plots, categorical plots, and Folium maps were created to explore relationships and patterns within the data.

This project aimed to leverage linear regression analysis to predict insurance costs based on various factors present in the medical cost dataset.
