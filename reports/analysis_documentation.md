# Global Economic Indicators Analysis – Technical Documentation

## 1. Project Objective
The objective of this project was to analyze global economic indicators and identify statistically significant relationships between GDP, trade balance, and other macroeconomic variables.
---

## 2. Data Cleaning & Preparation
The following preprocessing steps were applied:
- Removed unnecessary columns
- Standardized column names (removed spaces and ensured consistent formatting)
- Replaced missing values using median imputation
- Renamed columns for clarity and consistency
- Performed feature engineering (created log-transformed variables and derived indicators)

Libraries used:
- NumPy
- Pandas
- SciPy

## 3. Exploratory Data Analysis (EDA)
Several exploratory techniques were applied:
- Correlation analysis
- Boxplots for distribution and outlier detection
- Heatmap visualization for variable relationships
- Violin plots for distribution comparison
- Log-transformed GDP feature analysis
- Trade balance-focused visual analysis
- Top 10 GDP country comparisons
- Time-based economic trend visualizations

Visualization libraries:
- Matplotlib
- Seaborn
---
## 4. Statistical Analysis
Statistical methods included:
- Correlation coefficient analysis
- Distribution analysis through boxplots and violin plots
- Heatmap-based multivariable relationship assessment
- Log transformation for normalization purposes
---

## 5. Hypothesis Testing
Three statistical hypothesis tests were conducted to evaluate relationships between key economic indicators.

### Hypothesis 1: Household Consumption vs Government Consumption  
**Test Used:** Paired (Dependent) t-test  
- H0: There is no statistically significant difference between household consumption and government consumption.
- H1: There is a statistically significant difference between household consumption and government consumption.
A paired t-test was applied because both variables represent related economic measures observed within the same countries and periods.
The p-value was used to determine statistical significance.

### Hypothesis 2: GDP vs GNI  
**Test Used:** Pearson Correlation Analysis  
- H0: There is no linear relationship between GDP and GNI.
- H1: There is a statistically significant linear relationship between GDP and GNI.
Pearson correlation coefficient was calculated to assess the strength and direction of the relationship.

### Hypothesis 3: Population vs GDP Per Capita  
**Test Used:** Pearson Correlation Analysis  
- H0: There is no statistically significant linear relationship between population and GDP per capita.
- H1: There is a statistically significant linear relationship between population and GDP per capita.
Correlation strength and p-value were analyzed to validate statistical significance.

## 6. Power BI Dashboard Development
A multi-page interactive Power BI dashboard was developed to present macroeconomic insights visually.

### Page 1 – Global Economic Overview
- Total Global GDP (2021)
- Total number of countries
- Global population
- Top 10 countries by GDP
- EU consumption comparison (Government vs Household)
- Exports vs Imports comparison
- Global GDP map visualization
This page provides a high-level executive overview of global economic performance.

### Page 2 – Sector Analysis & Trends
- Sector share breakdown (Industry, Agriculture, Services, etc.)
- Time-series trend analysis (2010–2020)
- Country-specific sector visualization
- Pie chart sector distribution
This page focuses on structural economic composition and sectoral growth trends.

### Page 3 – Country-Level Deep Dive (Example: Azerbaijan)
- GDP and Population indicators
- Exports vs Imports over time
- Household vs Government consumption comparison
- Population vs GDP per capita trend analysis
This page enables country-level economic performance analysis.

## 7. Key Insights

- Strong correlation observed between GDP and selected investment indicators.
- Trade balance relationships vary across countries.
- Log transformation improved interpretability of skewed variables.
- Hypothesis testing validated statistically significant macroeconomic relationships.
