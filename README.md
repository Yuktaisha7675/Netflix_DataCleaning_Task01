# Netflix_DataCleaning_Task01
Data Analyst Internship Task 1 - Netflix Dataset Cleaning
# Task 1: Data Cleaning and Preprocessing – Netflix Movies and TV Shows

## 📊 Dataset
Netflix Movies and TV Shows from Kaggle  
Link: https://www.kaggle.com/datasets/shivamb/netflix-shows

## 🛠 Tools Used
- Python
- Pandas Library

## 🧹 Cleaning Steps Performed
- Handled missing values using `fillna()` and `ffill()`
- Removed duplicate rows using `drop_duplicates()`
- Standardized text fields (e.g., type, rating)
- Converted `date_added` to proper datetime format
- Renamed columns for consistency (e.g., lowercase, underscores)
- Exported cleaned dataset to `cleaned_netflix_titles.csv`

## 📁 Files Included
- `netflix_cleaning.ipynb`: Jupyter notebook with code
- `cleaned_netflix_titles.csv`: Cleaned dataset
- `README.md`: Summary of the task
