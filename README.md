# STATISTICAL ANALYSIS

INTODUCTION :
-
This activity explores a heart disease dataset using various statistical analysis methods. The primary goal is to understand the relationships between risk factors (such as cholesterol, age, and blood pressure) and the likelihood of heart disease. The analysis uses Python libraries such as Pandas, NumPy, Scipy, and Statsmodels.

The dataset used in this project is a Heart Disease dataset, which contains multiple variables related to patients' health conditions and whether or not they suffer from heart disease.

Key variables include :

Cholesterol Levels
Age,
Blood Pressure,
Heart Disease (Target Variable)

The dataset can be obtained from UCI Machine Learning Repository or other Kaggle.

Statistical Methods Used :
-
1. Descriptive Statistics :
Descriptive statistics such as mean, median, standard deviation, and quartiles were calculated for key variables (cholesterol, age, etc.) to understand their central tendency and spread.

2. Hypothesis Testing : 
A hypothesis test was performed to determine if the average cholesterol level in the population is significantly different from a specified value (e.g., 200 mg/dL).

- Null Hypothesis (H₀) : The mean cholesterol level is equal to 200 mg/dL.
- Alternative Hypothesis (H₁) : The mean cholesterol level is not equal to 200 mg/dL.

3. Confidence Intervals :
Confidence intervals were calculated to estimate the range within which the true population mean cholesterol is expected to fall with 95% confidence.

4. Regression Analysis :
Simple and Multiple Linear Regression models were used to study the relationship between risk factors (such as cholesterol and age) and the occurrence of heart disease.

- Simple Linear Regression : Cholesterol level as the predictor of heart disease.
- Multiple Linear Regression : Multiple factors (e.g., cholesterol, age, blood pressure) as predictors.

PREREQUISITES :
-
To run the analysis, you will need the following Python libraries:

- pandas
- numpy
- scipy
- statsmodels

RESULTS AND FINDINGS :
-
- Descriptive Statistics : The dataset shows a wide range of cholesterol levels, with the mean being higher than the recommended threshold.
- Hypothesis Testing : The hypothesis test showed that the mean cholesterol level is significantly higher than 200 mg/dL.
- Confidence Intervals : The 95% confidence interval for the mean cholesterol level was within a range that suggests high cholesterol is common in the population studied.
- Regression Analysis : Cholesterol, age, and blood pressure were found to be significant predictors of heart disease, with cholesterol having a strong positive correlation with heart disease risk.

CONCLUSION :
-
The statistical analysis of the heart disease dataset provided valuable insights into the relationships between risk factors like cholesterol and heart disease. Hypothesis testing confirmed that the average cholesterol level is significantly high, and regression analysis highlighted key predictors of heart disease. These findings can inform future medical research and public health initiatives focused on reducing the risk of heart disease.
