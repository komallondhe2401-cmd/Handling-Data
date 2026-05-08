**Handling Data**
## 📌 Project Overview
This project demonstrates different techniques of Handling Data using multiple datasets such as titanic.csv, orders.csv, and messages.csv.
The notebook focuses on handling mixed data, date variables, and time variables using Python libraries like Pandas, NumPy, and Datetime functions.

## 📂 Datasets Used
titanic.csv
orders.csv
messages.csv

## 🔹 Handling Mixed Data (titanic.csv)
In this section, mixed data containing both numerical and categorical values in a single column was handled.

✅ Tasks Performed
Identified columns containing mixed data types
Split one mixed column into:
  - Numerical column
  - Categorical column
Performed preprocessing and cleaning on extracted columns

🛠 Techniques Used
String operations
Regular Expressions
Pandas column transformation



## 🔹 Handling Date Variables (orders.csv)
Different date-related features were extracted from the dataset using Pandas datetime functions.
✅ Features Extracted
    Year
    Month
    Date
    Name of Month
    Day Number of Week
    Name of Day
    Is Weekend?
    Week of Year
    Quarter of Year
    Semester
    Time elapsed between current date and given date
    Number of months passed

🛠 Functions Used
    pd.to_datetime()
    .dt.year
    .dt.month
    .dt.day
    .dt.day_name()
    .dt.month_name()
    .dt.isocalendar()
    Timedelta operations


## 🔹 Handling Time Variables (messages.csv)
In this section, different components of time were extracted and analyzed.
✅ Features Extracted
      Hour
      Minutes
      Seconds
      AM/PM Time Format
      Time Differences
      Duration Calculations

🛠 Functions Used
      .dt.hour
      .dt.minute
      .dt.second
      Time difference calculations using datetime


## 📊 Libraries Used
Pandas
NumPy
Datetime


## 🎯 Key Learnings
Handling mixed datatype columns
Working with datetime objects
Extracting useful date and time features
Performing feature engineering on temporal data
Understanding real-world preprocessing techniques


## 🚀 Conclusion
This project provides practical implementation of handling mixed, date, and time data for machine learning and data preprocessing tasks. It helps in understanding feature engineering techniques commonly used in real-world datasets.
