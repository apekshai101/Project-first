# Project-first
Predicting the health risk factors for pregnant patients.
1.In this project we are going to predict whether health factors like age, systolic blood pressure, diastolic blood pressure , blood sugar, body temperature, and heart rate correlate with pregnancy risks.
2.To identify any health factors, have correlation with one another

# Data Source:
The data is taken from Kaggle website in form of csv file Maternal Health Risk Data Set.csv. This data has been collected from different hospitals, community clinics, maternal health cares through the IoT based risk monitoring system (Ahmed and Kashem, 2020; Ahmed et al., 2020). 
Data contains the following columns:
•    Age: Age in years when a woman is pregnant.
•    SystolicBP: Upper value of Blood Pressure in mmHg
•    DiastolicBP: Lower value of Blood Pressure in mmHg 
•    BS: Blood glucose levels is in terms of a molar concentration, mmol/L.
•    HeartRate: A normal resting heart rate in beats per minute.
•    Body Temperature: A normal body temperature in Fahrenheit.
•    Risk Level: Predicted Risk Intensity Level during pregnancy(high risk, mid risk and low risk).

# Prerequisites:
Certain libraries are needed to be installed before project:
•    Python 
•    Jupyter Notebook
•    Pandas
•    Matplotlip
•    Scipy.stats,numpy,seaborn
•    GitHub
Local git repository project first was created , cloned and changes were pushed to main branch.

# Objective:
1.Find correlation between health factors like age, systolic blood pressure, diastolic blood pressure, blood sugar levels, 
body temperature, heart rate with pregnancy risks level(high,mid,low).
2.To identify correlation between health factors by simple linear regression.

# Data Cleaning:
Data was uploaded from Maternal Health Risk Data Set.csv file and read into pandas dataframe.
Next data was cleaned by looking for null values and duplicated rows. Duplicated rows were found and dropped.

# Data Analysis:
1.Python script was created to calculate Quartiles(q1,q2 andq3), Interquartile Range(IQR), upper bound, lower bound and 
outlier for each health variable age, systolic BP, diastolic BP , Blood sugar, Heart rate, and body temperature.

2.Total percentage of females according to risk level were calculated and shown in form of pie chart.

3.Relationship between following health factors and risk level were shown by using different data visualization techniques 
  using matplotlip, seaborn, python and pandas:
Risk level and Age –  grouped bar plot used for visual data and pandas function for writing code
Risk level and Systolic BP – Boxplot were used for visual data and python for writing code
Risk level and Diastolic BP - Boxplot were used for visual data and python for writing code
Risk level and Blood Sugar – Scatter plot were used for visual data
Risk level and Heart rate – Scatter plot were used for visual data
Risk level and Body temperature – line plot were used for visual data

4.Correlation between following health variables were determined by using linear regression technique, scatter plot and 
finding “r value” to look for positive or negative correlation:
Age and Systolic BP
Age and Blood Sugar
Blood sugar and Systolic BP
Blood sugar and Diastolic BP
Heart rate and Blood sugar
Body temperature and Blood sugar
Systolic BP and Diastolic BP

#Analysis Summary:
A brief analysis summary was added in the maternal data.ipynb file in jupyter notebook as well as in Analysis Summary/.txt 
file. All the images were saved in png format, in Images folder.


