# 📊 Task 2 – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Advanced Exploratory Data Analysis (EDA)** on the Titanic dataset to understand data patterns, relationships, and survival trends.

The analysis includes data cleaning, statistical summaries, visualization, feature engineering, multicollinearity detection, and hypothesis testing.

---

## 🎯 Objectives

- Understand dataset structure  
- Generate descriptive statistics  
- Handle missing values  
- Detect and treat outliers  
- Identify feature relationships  
- Perform correlation analysis  
- Check multicollinearity (VIF)  
- Conduct hypothesis testing  
- Derive meaningful insights  

---

## 📂 Dataset

**Dataset Used:** Titanic Passenger Dataset  

The dataset contains information about passengers such as:

- Passenger ID  
- Age  
- Gender  
- Ticket Class (Pclass)  
- Fare  
- Number of Siblings/Spouses (SibSp)  
- Number of Parents/Children (Parch)  
- Embarked Port  
- Survival Status  

---

## 🛠 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- SciPy  
- Statsmodels  

---

## 🔎 Steps Performed

### 1️⃣ Data Inspection
- Checked dataset shape
- Reviewed data types
- Generated summary statistics
- Identified missing values

### 2️⃣ Data Cleaning
- Filled missing `Age` values using median
- Filled missing `Embarked` values using mode
- Dropped `Cabin` column (high percentage of missing values)

### 3️⃣ Feature Engineering
- Created `FamilySize` feature
- Created `IsAlone` feature
- Extracted `Title` from passenger names

### 4️⃣ Statistical Analysis
- Mean, Median, Standard Deviation
- Skewness detection
- Log transformation on skewed features
- IQR-based outlier detection

### 5️⃣ Visualization
- Histograms
- Boxplots
- Correlation heatmap
- Pairplot
- Survival rate by Gender
- Survival rate by Passenger Class
- Interactive Plotly visualization

### 6️⃣ Multicollinearity Check
- Calculated Variance Inflation Factor (VIF)

### 7️⃣ Hypothesis Testing
- Conducted T-Test to compare survival rates between males and females

---

## 📊 Key Insights

- Female passengers had significantly higher survival rates.
- First-class passengers had better survival probability.
- Fare distribution was right-skewed and required log transformation.
- Family size had an impact on survival probability.
- Statistical testing confirmed gender significantly influenced survival.

---

## 📁 Project Structure

