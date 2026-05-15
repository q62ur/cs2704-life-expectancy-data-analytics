# Predicting Global Life Expectancy Using Data Analytics

This project analyzes global life expectancy using socioeconomic and health-related indicators. The goal is to understand which factors are strongly connected to life expectancy and to build predictive models using Python.

## Project Links

- [View Notebook](FinalProject.ipynb)
- [View Dataset](data/life-expectancy-dataset.csv)

## Project Overview

Life expectancy can be influenced by many factors, including GDP, schooling, healthcare expenditure, mortality rates, disease prevalence and development status. In this project, I used data analytics and machine learning techniques to explore these relationships and predict life expectancy trends.

The project focuses on the question:

**Can life expectancy be predicted reliably using measurable country-level data?**

## Dataset

The dataset contains country level life expectancy information along with socioeconomic and health indicators. Some of the main variables include:

- Life expectancy
- GDP
- Schooling
- Adult mortality
- Infant deaths
- HIV/AIDS
- BMI
- Total expenditure
- Country status
- Year

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Main Steps

1. **Data Collection**
   - Loaded the life expectancy dataset into Python using Pandas.

2. **Data Cleaning**
   - Checked missing values.
   - Handled missing numerical and categorical data.
   - Converted data types where needed.
   - Created a life expectancy category for classification.

3. **Exploratory Data Analysis**
   - Generated summary statistics.
   - Created correlation analysis.
   - Used visualizations such as heatmaps and scatter plots to study relationships between variables.

4. **Feature Preparation**
   - Selected important predictors.
   - Encoded categorical data.
   - Split the data into training and testing sets.
   - Scaled numerical features for machine learning models.

5. **Modeling**
   - Built a regression model to predict numeric life expectancy.
   - Built classification models to classify life expectancy into categories.

## Models Used

### Regression
- Linear Regression

### Classification
- Logistic Regression
- Support Vector Machine
- Gaussian Naive Bayes

## Key Findings

- Schooling and GDP showed strong positive relationships with life expectancy.
- Adult mortality, HIV/AIDS and infant deaths showed negative relationships with life expectancy.
- Linear Regression was useful for predicting numeric life expectancy.
- SVM performed strongly for classifying life expectancy categories.

## Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- Data visualization
- Regression modeling
- Classification modeling
- Model evaluation
- Python programming

## Project Files

```text
cs2704-life-expectancy-data-analytics/
│
├── FinalProject.ipynb
├── README.md
└── data/
    └── life-expectancy-dataset.csv
