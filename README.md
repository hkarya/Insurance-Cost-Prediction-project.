 End-to-End Insurance Data Pipeline Project

A Python-based data analysis and feature engineering project that explores medical insurance data to understand the factors associated with individual insurance charges. The project applies exploratory data analysis (EDA), data cleaning, categorical encoding, feature engineering, feature scaling, and statistical testing to prepare data for further machine learning.

 Project Overview

The project uses the medical insurance dataset containing 1,338 records and 7 columns. It explores how demographic and lifestyle factors, including age, BMI, smoking status, number of children, sex, and residential region, relate to insurance charges.

 Dataset Features

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `sex` | Sex of the individual |
| `bmi` | Body Mass Index |
| `children` | Number of children or dependents |
| `smoker` | Smoking status |
| `region` | Residential region |
| `charges` | Individual medical insurance charges (target variable) |

 Key Features

- Exploratory Data Analysis (EDA):** Examined dataset structure, descriptive statistics, distributions, and feature relationships.
- Data Cleaning:** Checked missing values and removed duplicate records.
- Data Visualization:** Used histograms, count plots, box plots, and a correlation heatmap to explore the data.
- Categorical Encoding:** Applied mapping and one-hot encoding to categorical features.
- Feature Engineering:** Created BMI categories, including underweight, normal, overweight, and obese.
- Feature Scaling:** Applied `StandardScaler` to numerical features such as age, BMI, and number of children.
- Pearson Correlation Analysis:** Examined linear relationships between selected features and insurance charges.
- Chi-Square Testing:** Tested associations between categorical features and categorized insurance-charge groups using a significance level of 0.05.
- Feature Selection:** Used statistical analysis to help identify features for further analysis.

 Exploratory Findings

The Pearson correlation analysis in the notebook showed the following relationships with insurance charges:

| Feature | Pearson Correlation |
|---|---:|
| Smoking status | 0.787 |
| Age | 0.298 |
| BMI | 0.196 |

These results indicate that smoking status had the strongest positive linear association with insurance charges among the listed features, followed by age and BMI. Correlation indicates association, not causation.

The chi-square analysis also examined relationships between categorical features and insurance-charge groups.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

 Project Workflow

Data Loading → Exploratory Data Analysis → Data Cleaning → Categorical Encoding → BMI Feature Engineering → Feature Scaling → Statistical Analysis → Feature Selection

 Skills Demonstrated

Python programming, data manipulation, data quality checks, data visualization, exploratory data analysis, feature engineering, statistical hypothesis testing, and data preprocessing.

Future Improvements

- Refine categorical encoding and validate the preprocessing pipeline.
- Build and compare regression models for predicting insurance charges.
- Evaluate predictive performance using appropriate regression metrics.
- Validate feature selection and preprocessing choices before final model training.
- 

This project demonstrates a practical workflow for exploring, cleaning, analyzing, and preparing real-world tabular data for machine learning.
