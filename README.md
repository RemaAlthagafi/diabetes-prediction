# Diabetes Prediction

## Project Overview

This project focuses on building a machine learning model to predict diabetes using medical features such as glucose level, insulin, BMI, blood pressure, age, and pregnancies. The objective was to clean and prepare the dataset, explore patterns in the data, and support the development of a reliable prediction system.

---

## Dataset:
The dataset used for this project is available on Kaggle. You can access it using the following link:
[Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset?select=diabetes.csv)

Key features include:

- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- Age  
- Pregnancies  

---

## My Contribution

I was responsible for the data preprocessing phase, where I identified invalid zero values in key medical features and replaced them with NaN, applied median imputation to handle missing data, removed redundant columns, converted categorical labels into numerical format, and prepared a clean and structured dataset ready for machine learning modeling.

---

## Data Preprocessing

Several important medical columns contained invalid zero values, including Glucose, BloodPressure, SkinThickness, Insulin, and BMI. These values were treated as missing data and handled using median imputation to ensure consistency and reliability. The dataset was then formatted and structured appropriately for further analysis and modeling.

---

## Exploratory Data Analysis

The dataset was explored using statistical summaries and visualization techniques, including:

- Statistical summary using `describe()`  
- Feature distribution analysis with histograms  
- Class comparison using boxplots  
- Relationship analysis using scatter plots  

These analyses helped reveal patterns and differences between diabetic and non-diabetic patients.

---

## Conclusion

This project highlights the importance of proper data cleaning and preprocessing in healthcare prediction systems. Accurate data preparation plays a critical role in improving the reliability and effectiveness of machine learning models.