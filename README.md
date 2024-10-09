**Project Title: Predicting Crime Type and District in Chicago Using Machine Learning**

**Project Overview:**
This project focuses on predicting crime types and districts in Chicago based on daily crime data spanning from 2001 to 2022. The Chicago Police Department (CPD) seeks insights to reduce the occurrence of violent crimes by understanding patterns of criminal activity, locations, and time periods where they are most likely to happen. The CPD aims to use these insights for efficient resource allocation and response strategies.

**Objective:**
To conduct a full data analytics process and develop predictive models to help the CPD:
- Identify types of crimes to anticipate.
- Determine the most likely districts for criminal activities.
- Predict the days of the week and periods when crimes are more frequent.

**Tools Used:**
- Python Programming
- Chicago Crime Dataset

**Key Features of the Data:**
- Dataset size: 2,278,726 rows and 23 columns
- Date range: 2001 to 2022
- Crime types, locations (latitude, longitude), arrest records, domestic cases, police district data, and more

**Steps Undertaken:**
1. **Data Cleaning**: Handled missing values (less than 2% missing), removed duplicates, and processed date columns for analysis.
2. **Data Exploration**: Normalized and standardized the data to account for outliers and non-normal distributions.
3. **Feature Engineering**: Selected key features such as District, Crime Type, and Day using Recursive Feature Elimination.
4. **Model Development**: Used Decision Tree Classifier, Random Forest, and CatBoost models for predictions.

**Model Performance:**
- **District**: Random Forest achieved 98% accuracy with an MSE of 0.064.
- **Crime Type**: Decision Tree Classifier achieved 79% accuracy with an MSE of 28.
- **Day Prediction**: CatBoost model achieved 13% accuracy with an MSE of 15.

This project has successfully created predictive models that provide actionable insights for the Chicago Police Department to combat crime more effectively.
