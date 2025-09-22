# Elevate_Labs_Task_1
# 🧹 Data Cleaning Project - Medical Appointment No Shows
## 📌 About This Project
This project was completed as part of a **Data Analyst Internship Task**.  
The goal was to take a raw dataset, clean it up, and make it ready for analysis or modeling.
The dataset I worked with is the popular **Medical Appointment No Shows** dataset from Kaggle.
---
## 🔧 What I Did
Here’s a quick rundown of the cleaning steps I performed:
- **Cleaned up column names** → made everything lowercase, replaced spaces with underscores, and fixed typos (e.g., `hipertension` → `hypertension`, `handcap` → `handicap`).  
- **Standardized values** → made sure gender was only `Male` or `Female`, and the `no-show` column had just `Yes` / `No`.  
- **Fixed invalid data** → removed rows where age was negative.  
- **Formatted dates** → converted `scheduledday` and `appointmentday` into proper datetime format.  
- **Checked for duplicates** → none were found, but I still verified.  
---
## 📊 Final Dataset Overview
- **Rows:** 110,526  
- **Columns:** 14  
- **Age Range:** 0 to 115  
- **Missing Values:** None  
- **Duplicates:** None  
---
## 📁 Repository Contents
- `KaggleV2-May-2016.csv` → Original raw dataset  
- `KaggleV2-May-2016-cleaned` → Final cleaned dataset  
- `README.md` → Project summary (this file)
- `Task_1` → Python Code
---
## 💡 Practice Interview Questions
As part of the task, here are some common questions related to data cleaning:  
1. What are missing values and how can you handle them?  
2. How do you deal with duplicate records in a dataset?  
3. What’s the difference between `dropna()` and `fillna()` in Pandas?  
4. What is outlier treatment and why does it matter?  
5. What does it mean to standardize data?  
6. How would you handle inconsistent date or time formats?  
7. What are some common challenges you face when cleaning data?  
8. How can you check if your data is high quality?  
---
## ✅ Wrap Up
This dataset is now **clean, structured, and analysis-ready**.  
The process gave me hands-on experience with handling missing values, standardizing formats, and ensuring overall data quality.
---
