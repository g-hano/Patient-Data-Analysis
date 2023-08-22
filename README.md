---

# Hospital Data Analysis Project

## Overview

This project involves the analysis of hospital [data](https://www.kaggle.com/datasets/nanditapore/medical-cost-dataset) obtained from Kaggle. The dataset contains information about patients, including their patient ID, sex, BMI, age, region, smoking status, and total medical charges. The analysis was conducted using Python, utilizing libraries such as NumPy, Pandas, Matplotlib, and Seaborn for data exploration and visualization.

## Data Cleaning and Exploration

1. **Data Integrity Check**: The dataset was examined to ensure data integrity. Duplicate patient records were checked for and found to be absent.

2. **Bias Assessment**: A thorough examination was conducted to identify any potential biases in the data collection process, which, fortunately, were not found. This ensures the trustworthiness of the dataset.

3. **Missing Values**: All columns were checked for missing values, and none were detected.

4. **Gender Distribution**: An analysis was performed to determine the distribution of genders in the dataset, revealing only two genders, as expected.

5. **Data Manipulation Strategies (if necessary)**: Although the dataset was clean, contingency plans were made for data manipulation if required. These included removing rows with duplicated patient IDs, handling missing values in the age and BMI columns by filling with means, and deleting rows with missing region data.

## Data Visualization

1. **Top Smokers in Each Region**: A new DataFrame was created to identify the top 10 smokers in each region. It was found that they were all male with an average age of 18 and a high average BMI of 36.344. This information can be used to advocate for healthy habits among teenagers.

2. **Regional Smoking Habits**: A pie chart was generated to visualize the percentage of smokers and non-smokers in different regions. This analysis indicated that eastern regions had a higher percentage of smokers (approximately 28%) compared to south and northwest regions (approximately 22%).

3. **BMI vs. Gender**: A comparison of BMI between genders revealed that males tended to have higher BMIs and higher smoking rates.

4. **Correlation Analysis**: Correlation between BMI and medical charges was investigated and found to be weak, leading to the conclusion that other factors may influence medical charges more significantly.

5. **Top 5 Highest Charged Patients**: The top 5 highest-charged patients were identified, with notable characteristics including a mean age of 18, all being male, having no children, a mean BMI of 36.344, and all being smokers.

## Conclusion

This data analysis project provides valuable insights into the hospital data, highlighting trends related to smoking, gender, BMI, and medical charges. These findings can be used for further research or to inform healthcare decisions and public health initiatives.

---
