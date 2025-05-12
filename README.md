# Driver Attrition Prediction

# Project Overview
This project aims to predict driver attrition for Ola, a prominent ride-hailing platform, by analyzing monthly driver-level data from 2019 and 2020. The objective is to predict whether a driver is likely to disengage or leave the platform based on various factors such as demographics, tenure, and performance metrics. Understanding these patterns is vital, as high driver turnover can undermine driver satisfaction and significantly increase the costs associated with recruiting and onboarding replacements.

# Data set
The dataset includes the following key features:

•	MMMM-YY: Reporting date (monthly)

•	Driver_ID: Unique identifier for drivers

•	Age: Driver's age

•	Gender: Gender (0: Male, 1: Female)

•	City: City code

•	Education_Level: Education level (0: 10+, 1: 12+, 2: Graduate)

•	Income: Monthly average income of the driver

•	Date_Of_Joining: Joining date of the driver

•	LastWorkingDate: Last working date (if applicable)

•	Joining Designation: Designation at the time of joining

•	Grade: Grade at the time of reporting

•	Total Business Value: Total business value acquired by the driver in a month

•	Quarterly Rating: Quarterly rating (1 to 5, higher is better)


# Key concepts

•	Exploratory Data Analysis (EDA): Examine the dataset's structure and characteristics.

•	Feature Engineering: Create new features such as income growth and quarterly rating improvement.

•	Class Imbalance Treatment: Apply appropriate methods to handle imbalanced classes.

•	Ecncoding and Scaling the features.

•	Modeling: Use ensemble learning methods (Bagging, Boosting) to predict driver attrition.

•	Evaluation: Evaluate model performance using classification reports and ROC AUC curves.

# Requirements
● Python 3.x

● Libraries: pandas, numpy, matplotlib, seaborn, category_encoders, scikit-learn, statsmodels






