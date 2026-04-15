# 📊 Netflix Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project is part of the Synent Technologies Data Science Internship (Task 3).  
The goal is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify trends, patterns, and insights.

---

## Objective
- Analyze the dataset using summary statistics  
- Study relationships using correlation analysis  
- Identify trends and patterns in Netflix content  

---

## 📂 Dataset
**Name:** Netflix Dataset  

**Features:**
- show_id  
- type  
- title  
- director  
- cast  
- country  
- date_added  
- release_year  
- rating  
- duration  
- listed_in  
- description  

---

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

##  Steps Performed

### 1. Data Loading
- Loaded dataset using Pandas  
- Previewed data using head(), info(), and describe()

### 2. Data Cleaning
- Checked for missing values  
- Handled null values using fillna()  
- Used:
  - 'Unknown' for categorical columns  
  - Mode for minimal missing values  
  - Forward fill for date column  

### 3. Exploratory Data Analysis
- Analyzed content distribution (Movies vs TV Shows)  
- Identified top content-producing countries  
- Studied content growth over the years  
- Analyzed ratings distribution  

### 4. Correlation Analysis
- Performed correlation on numerical data  
- Observed limited insights due to mostly categorical features  

---

## Key Insights
- Movies are more than TV Shows on Netflix  
- Content increased rapidly after 2015  
- United States produces the highest content  
- Most content is rated TV-MA (mature audience)  
- Correlation analysis is limited due to categorical data  

---

## 📈 Visualizations
The project includes:
- Count plots  
- Bar charts  
- Line graphs  
- Heatmap  

---

## Conclusion
This analysis helps in understanding Netflix’s content distribution, growth trends, and audience targeting strategy.

---
