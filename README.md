# Heart Disease Analysis

## Overview
This project aims to analyze the Heart Disease dataset to uncover patterns and relationships between various health indicators and the presence of heart disease. The analysis involves data cleaning, exploratory data analysis (EDA), and regression analysis.

## Dataset
The dataset contains various health-related attributes of patients, including:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure (RestingBP)
- Serum Cholesterol Levels
- Fasting Blood Sugar (FastingBS)
- Resting Electrocardiogram (RestingECG) Results
- Maximum Heart Rate (MaxHR)
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- ST Segment Slope
- Heart Disease Status (1: Heart Disease, 0: Normal)

## Data Cleaning
Data cleaning steps included:
1. **Handling Missing Values**: Checked for and addressed any missing values in the dataset.
2. **Removing Duplicates**: Identified and removed duplicate records to ensure data quality.
3. **Data Type Conversion**: Ensured appropriate data types for each feature.

## Exploratory Data Analysis (EDA)
### Age Distribution
- **Question**: What is the distribution of ages among the patients in the dataset?
- **Question**: Is there a difference in age distribution between patients with heart disease and those without?

### Sex Distribution
- **Question**: How many male and female patients are included in the dataset?
- **Question**: Is there any gender imbalance in the occurrence of heart disease?

### Chest Pain Type Analysis
- **Question**: What are the frequencies of different chest pain types (Typical Angina, Atypical Angina, Non-Anginal Pain, Asymptomatic)?
- **Question**: Is there an association between chest pain type and the presence of heart disease?

### Resting Blood Pressure (RestingBP) Analysis
- **Question**: What is the distribution of resting blood pressure among patients?
- **Question**: Are patients with heart disease more likely to have higher resting blood pressure?

### Cholesterol Level Analysis
- **Question**: What is the distribution of serum cholesterol levels among patients?
- **Question**: Is there a difference in cholesterol levels between patients with and without heart disease?

### Fasting Blood Sugar (FastingBS) Analysis
- **Question**: What proportion of patients have fasting blood sugar levels above 120 mg/dl?
- **Question**: Is there a correlation between fasting blood sugar levels and the presence of heart disease?

### Resting Electrocardiogram (RestingECG) Analysis
- **Question**: What are the frequencies of different resting electrocardiogram results (Normal, ST-T wave abnormality, Left Ventricular Hypertrophy)?
- **Question**: Is there an association between abnormal resting electrocardiogram results and heart disease?

### Maximum Heart Rate (MaxHR) Analysis
- **Question**: What is the distribution of maximum heart rates achieved by patients?
- **Question**: Is there a difference in maximum heart rates between patients with heart disease and those without?

### Exercise-Induced Angina (ExerciseAngina) Analysis
- **Question**: What proportion of patients experience exercise-induced angina?
- **Question**: Is exercise-induced angina more common among patients with heart disease?

### Oldpeak (ST Depression) Analysis
- **Question**: What is the distribution of ST depression values among patients?
- **Question**: Is there a correlation between ST depression and the presence of heart disease?

### ST Segment Slope (ST_Slope) Analysis
- **Question**: What are the frequencies of different ST segment slope types (Upsloping, Flat, Downsloping)?
- **Question**: Is there an association between ST segment slope and the likelihood of heart disease?

### Heart Disease Distribution
- **Question**: What is the overall distribution of heart disease status (1: Heart Disease, 0: Normal) in the dataset?
- **Question**: Are there any notable trends or patterns in the occurrence of heart disease based on other features?

## Regression Analysis
### Question A
**Question**: How does maximum heart rate achieved (MaxHR) relate to the likelihood of heart disease, considering age and Sex as potential predictors?

Performed logistic regression to analyze the relationship between MaxHR, age, sex, and the likelihood of heart disease.

### Question B
**Question**: Does the maximum heart rate achieved during exercise (MaxHR) predict the likelihood of heart disease, considering age as a potential confounding factor?

Conducted logistic regression to evaluate the impact of MaxHR and age on the likelihood of heart disease.

## Libraries Used
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations.
- **matplotlib**: Data visualization.
- **seaborn**: Statistical data visualization.
- **scipy**: Scientific and technical computing.
- **statsmodels**: Statistical modeling and hypothesis testing.

## Conclusion
This project provided insights into the relationships between various health indicators and heart disease. The analysis included detailed EDA and regression analysis to understand these relationships better.

## Usage
To run the analysis, ensure you have the required libraries installed. You can install them using:
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels
