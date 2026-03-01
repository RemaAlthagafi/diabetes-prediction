# Diabetes Prediction

## Project Overview

This project focuses on analyzing, visualizing, and predicting diabetes risk using patient data. We built a **Logistic Regression** model and evaluated its performance using the **F1 score**. ---

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

I was responsible for the **data preprocessing** phase, where I identified invalid zero values in key medical features and replaced them with NaN, applied median imputation to handle missing data, removed redundant columns, converted categorical labels into numerical format, and prepared a clean and structured dataset ready for machine learning modeling.

---

## Data Preprocessing

Several important medical columns contained invalid zero values, including Glucose, BloodPressure, SkinThickness, Insulin, and BMI. These values were treated as missing data and handled using median imputation to ensure consistency and reliability. The dataset was then formatted and structured appropriately for further analysis and modeling.

---

## Machine Learning Model

We used a **Logistic Regression** model to predict diabetes risk. Although the focus was on data preprocessing, we also evaluated the model's performance using the **F1 score**, ensuring that the model's predictions were balanced between precision and recall.

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

This project highlights the importance of **data cleaning**, **preprocessing**, and **visualization** in healthcare prediction systems. Although machine learning models were used, the primary focus was on improving the quality and structure of the data, which plays a critical role in enhancing the reliability and effectiveness of any prediction system.