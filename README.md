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
- <img width="1920" height="1080" alt="Screenshot 2026-05-07 091558" src="https://github.com/user-attachments/assets/b4551ab5-9e19-4c25-b13d-db5270a3ab0a" />
  
- Bar charts
- <img width="1920" height="1080" alt="Screenshot 2026-05-07 091610" src="https://github.com/user-attachments/assets/329fcb60-45b0-4411-a239-699d5b5ac8b4" />

<img width="1920" height="1080" alt="Screenshot 2026-05-07 091627" src="https://github.com/user-attachments/assets/b6f6f4d1-2210-466f-ae1f-de9ff866d950" />

 
- Line graphs
- <img width="1920" height="1080" alt="Screenshot 2026-05-07 091620" src="https://github.com/user-attachments/assets/1d42bf25-8891-4e59-87f3-041e159c5325" />
  
- Heatmap  
<img width="1920" height="1080" alt="Screenshot 2026-05-07 091635" src="https://github.com/user-attachments/assets/3c34b67d-fd37-4c67-81fb-df0ae018139c" />

---

## Conclusion
This analysis helps in understanding Netflix’s content distribution, growth trends, and audience targeting strategy.

---
