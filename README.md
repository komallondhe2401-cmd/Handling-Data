# Handling Data

## 📌 Project Overview
This project demonstrates different techniques of handling data using multiple datasets such as `titanic.csv`, `orders.csv`, and `messages.csv`.

The notebook focuses on:
- Handling mixed data
- Handling date variables
- Handling time variables
- Feature engineering using Pandas and Datetime functions

---

# 📂 Datasets Used

- `titanic.csv`
- `orders.csv`
- `messages.csv`

---

# 🔹 Handling Mixed Data (`titanic.csv`)

In this section, mixed data containing both numerical and categorical values in a single column was handled.

## ✅ Tasks Performed

- Identified columns containing mixed datatype values
- Split one mixed column into:
  - Numerical column
  - Categorical column
- Cleaned and transformed extracted values
- Performed preprocessing on separated columns

## 🛠 Techniques Used

- String Operations
- Regular Expressions
- Pandas Transformations

---

# 🔹 Handling Date Variables (`orders.csv`)

Different useful date-related features were extracted from the dataset.

## ✅ Features Extracted

- Year
- Month
- Date
- Name of Month
- Day Number of Week
- Name of Day
- Is Weekend?
- Week of Year
- Quarter of Year
- Semester
- Time elapsed between current date and given date
- Number of months passed

## 🛠 Functions Used

- `pd.to_datetime()`
- `.dt.year`
- `.dt.month`
- `.dt.day`
- `.dt.day_name()`
- `.dt.month_name()`
- `.dt.isocalendar()`
- Timedelta operations

---

# 🔹 Handling Time Variables (`messages.csv`)

In this section, various time components were extracted and analyzed.

## ✅ Features Extracted

- Hour
- Minutes
- Seconds
- AM/PM Time Format
- Time Difference
- Duration Calculations

## 🛠 Functions Used

- `.dt.hour`
- `.dt.minute`
- `.dt.second`
- Datetime difference operations

---

# 📊 Libraries Used

- Pandas
- NumPy
- Datetime

---

# 🎯 Key Learnings

- Handling mixed datatype columns
- Working with datetime objects
- Extracting meaningful date and time features
- Performing feature engineering
- Understanding real-world preprocessing techniques

---

# 🚀 Conclusion

This project demonstrates practical implementation of handling mixed, date, and time data using Python and Pandas. It provides a strong foundation for data preprocessing and feature engineering in machine learning projects.
