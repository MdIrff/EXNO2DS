# EXNO2DS

# AIM:
```
To perform Exploratory Data Analysis on the given Titanic data set.
```

# EXPLANATION:
The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.

# ALGORITHM:
**STEP 1:** Import the required packages (Pandas, NumPy, Matplotlib and Seaborn) to perform Data Cleansing and Exploratory Data Analysis.

**STEP 2:** Load the Titanic dataset and understand it using head, shape, columns, info and describe.

**STEP 3:** Check the dataset for missing values and duplicate records, and remove the duplicates.

**STEP 4:** Replace the null values using the median (Age), mode (Embarked) and a constant value "Unknown" (Cabin), based on the dataset available.

**STEP 5:** Use the Countplot method to analyze the categorical data (Survived, Sex and Pclass) in a graphical way.

**STEP 6:** Use the Histplot method to represent the univariate distribution of Age and Fare.

**STEP 7:** Use the Boxplot method to analyze the outliers of Age and Fare.

**STEP 8:** Use the Heatmap method to show the correlation between the numerical variables.

**STEP 9:** Use the groupby method to quantitatively analyze the survival percentage by Sex, Pclass and Embarked.

# CODING AND OUTPUT

<img width="1530" height="649" alt="01_import_load_head" src="https://github.com/user-attachments/assets/768a5690-97b5-4963-ace1-9f42fe82d2fa" />

<img width="1030" height="256" alt="02_shape_columns" src="https://github.com/user-attachments/assets/cdf36a49-10df-47ef-bc6a-1bd728e40f47" />

<img width="1030" height="737" alt="03_info_describe" src="https://github.com/user-attachments/assets/2c470082-234c-44c7-ab80-ba39760fead7" />

<img width="1030" height="886" alt="04_missing_duplicates" src="https://github.com/user-attachments/assets/1c663d52-2883-4c48-81bc-1706d0864def" />


<img width="1030" height="727" alt="05_data_cleaning" src="https://github.com/user-attachments/assets/9b512244-4ce1-480a-a5be-55bb805a5ba6" />


<img width="1030" height="604" alt="06_countplot_survived" src="https://github.com/user-attachments/assets/3b6f2eeb-81f3-47b2-aed4-dfa65035cdb8" />

<img width="1030" height="604" alt="07_countplot_gender" src="https://github.com/user-attachments/assets/ed899c03-5f2f-494a-96a6-ad699e972d33" />

<img width="1030" height="604" alt="08_countplot_class" src="https://github.com/user-attachments/assets/1b095ff9-a8d2-41d6-86d5-80b54c771b95" />

<img width="1030" height="590" alt="09_age_distribution" src="https://github.com/user-attachments/assets/ecf57a62-d722-49c6-8bdd-eb946a3de071" />

<img width="1030" height="590" alt="10_fare_distribution" src="https://github.com/user-attachments/assets/c7bce1f1-4c1f-4410-88d3-659eefc7ed0a" />

<img width="1030" height="571" alt="11_age_boxplot" src="https://github.com/user-attachments/assets/9b3e8d1f-01fa-4194-be99-2c71b8a8f4e0" />

<img width="1030" height="571" alt="12_fare_boxplot" src="https://github.com/user-attachments/assets/4b34872b-9070-4557-948f-af8743a3879d" />

<img width="1030" height="967" alt="13_correlation" src="https://github.com/user-attachments/assets/b1bebe37-dd32-471c-93f2-e074e4bd0be8" />

<img width="1030" height="574" alt="14_survival_rates" src="https://github.com/user-attachments/assets/6a4bc0ba-13f9-467f-9c60-8ff218c81bbe" />

<img width="1030" height="749" alt="15_eda_summary" src="https://github.com/user-attachments/assets/ccc49fa1-efcc-4024-9109-5caf731bcc8d" />


# Summary of Work Performed
- Loaded the Titanic dataset (891 passengers, 12 columns) and explored its structure.
- Found no duplicate records; handled missing values in **Age** (177, filled with median), **Embarked** (2, filled with mode) and **Cabin** (687, filled with "Unknown"). The final dataset has no missing values.
- Of 891 passengers, **342 survived** and **549 did not**.
- **Gender:** about 74.2% of females survived compared with only 18.9% of males.
- **Passenger class:** survival fell from 63.0% (1st class) to 47.3% (2nd class) and 24.2% (3rd class).
- **Port of embarkation:** passengers from Cherbourg (C) had the highest survival rate (55.4%), compared with Queenstown (39.0%) and Southampton (33.9%).
- **Correlation:** Fare has a positive correlation with Survived (0.26), and Pclass a negative one (-0.34). Pclass and Fare are strongly negatively correlated (-0.55).
- The boxplots show outliers in both Age (older passengers) and Fare (a few very high fares).

# Result
Thus, Exploratory Data Analysis was successfully performed on the Titanic dataset.
