# 🌍 Global Economic Indicators Analysis

## 📌 Project Overview

This project presents a complete end-to-end global macroeconomic data analysis pipeline using **Python, Excel, and Power BI**.

The main objective is to analyze global economic indicators and identify statistically significant relationships between:

- GDP  
- Trade Balance  
- Household & Government Consumption  
- GNI  
- Population  
- GDP per Capita  

The project combines data preprocessing, exploratory analysis, statistical hypothesis testing, and business intelligence dashboard development.

---

## 🧹 Data Cleaning & Preparation (Python – Google Colab)

The dataset was preprocessed using:

- Removal of unnecessary columns  
- Standardization of column names  
- Median imputation for missing values  
- Column renaming for clarity  
- Feature engineering  
- Log transformation of skewed variables  

### 📚 Libraries Used

- NumPy  
- Pandas  
- SciPy  
- Matplotlib  
- Seaborn  

---

## 📊 Exploratory Data Analysis (EDA)

The following analytical techniques were applied:

- Correlation analysis  
- Boxplots (distribution & outlier detection)  
- Heatmaps (multivariable relationships)  
- Violin plots (distribution comparison)  
- Log-transformed GDP analysis  
- Trade balance visual analysis  
- Top 10 GDP country comparisons  
- Time-series economic trend analysis  

---

## 📈 Statistical Hypothesis Testing

Three key hypotheses were tested to evaluate macroeconomic relationships.

### 1️⃣ Household vs Government Consumption  
**Test Used:** Paired (Dependent) t-test  

- **H₀:** There is no statistically significant difference between household consumption and government consumption.  
- **H₁:** There is a statistically significant difference between household consumption and government consumption.  

A paired t-test was applied because both variables represent related economic measures within the same countries and periods.

---

### 2️⃣ GDP vs GNI  
**Test Used:** Pearson Correlation  

- **H₀:** There is no linear relationship between GDP and GNI.  
- **H₁:** There is a statistically significant linear relationship between GDP and GNI.  

Pearson correlation coefficient and p-value were calculated to assess strength and statistical significance.

---

### 3️⃣ Population vs GDP per Capita  
**Test Used:** Pearson Correlation  

- **H₀:** There is no statistically significant linear relationship between population and GDP per capita.  
- **H₁:** There is a statistically significant linear relationship between population and GDP per capita.  

Correlation strength and p-value were analyzed to validate statistical significance.

---

## 📊 Power BI Dashboard

A multi-page interactive dashboard was developed to present macroeconomic insights visually.

### 🌎 Page 1 – Global Economic Overview

- Total Global GDP (2021)  
- Total number of countries  
- Global population  
- Top 10 countries by GDP  
- EU consumption comparison (Government vs Household)  
- Exports vs Imports comparison  
- Global GDP map visualization  

![Dashboard Page 1](visuals/dashboard.page1.png)

---

### 🏭 Page 2 – Sector Analysis & Trends

- Sector share breakdown (Industry, Agriculture, Services)  
- Time-series trend analysis (2010–2020)  
- Country-specific sector visualization  
- Pie chart sector distribution  

![Dashboard Page 2](visuals/dashboard.page2.png)

---

### 🇦🇿 Page 3 – Country-Level Analysis (Example: Azerbaijan)

- GDP and Population indicators  
- Exports vs Imports over time  
- Household vs Government consumption comparison  
- Population vs GDP per capita trend analysis  

![Dashboard Page 3](visuals/dashboard.page3.png)

---

## 📊 Excel Pivot Analysis

Three structured pivot analyses were created:

- Trade Balance comparison  
- GDP vs GNI comparison  
- Population vs GDP analysis  

---

## 🔎 Key Insights

- Strong correlation observed between GDP and selected investment indicators  
- Trade balance relationships vary across countries  
- Log transformation improved interpretability of skewed variables  
- Hypothesis testing validated statistically significant macroeconomic relationships  

---

## 🛠 Tools & Technologies

- Python (NumPy, Pandas, SciPy, Matplotlib, Seaborn)  
- Google Colab  
- Microsoft Excel  
- Power BI  

---


