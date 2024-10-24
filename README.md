# **UK House Prices Data Analysis Project**

## **Project Overview**

This project aims to analyze UK house prices from 1995 onwards, incorporating elements of **data analysis** and **data engineering** with a focus on **big data processing**. The goal is to explore the relationship between various factors such as area, house type, and local variables to assess their influence on house prices. Additionally, we aim to forecast future house price trends based on historical data.

### **Key Objectives:**
1. **Correlation Analysis**: Investigate if there is a correlation between geographical areas (e.g., county, region) and house prices.
2. **Co-Variables**: Explore how other variables such as property type, tenure, and year influence house prices.
3. **Price Forecasting**: Develop models to predict future house prices based on previous trends using machine learning techniques.

---

## **Technology Stack**

To handle large datasets efficiently and ensure robust analysis, I utilsed  **Polars**, and **Pandas**

### **1. Data Integration and Engineering:** 
- **Polars**: Although Apache Spark will manage most of the large data processing, **Polars** may be used for initial explorations, data validation, and rapid manipulations. Polars is known for its fast execution and lower memory consumption on single-node environments.

- **Pandas**: While considered less likely due to its memory limitations, **Pandas** will still be explored for smaller data manipulations and exploratory data analysis (EDA) where applicable.

### **2. Data Analysis and Statistical Exploration:**
- **NumPy**: Utilized for numerical operations and efficient handling of arrays in conjunction with the larger datasets.
  
- **Seaborn & Matplotlib**: These libraries will be used for generating static visualizations, such as correlation heatmaps, regression plots, and histograms, to uncover potential relationships between variables.

### **3. Visualization and Dashboarding:**
- **Power BI**: / **Tableau** Considered as an option to enhance data visualizations through interactive dashboards. It will allow the exploration of the relationships between house prices and other variables in an engaging and user-friendly manner. This tool will provide end users with the ability to interactively filter data, making the insights more accessible.
  
- **Matplotlib/Seaborn**: For static, publication-ready visualizations, these Python libraries will be the go-to. Seaborn, in particular, is effective for correlation plots and pair-wise relationships.

---

## **Project Phases**

### **Phase 1: Data Engineering**
- **Data Loading**: Extract CSV files containing house price data from 1995 and 2013.
- **Data Cleaning & Preprocessing**: Handle missing values, standardize column formats, and normalize data for merging.
- **Merging Datasets**: Using Polarss where applicable, merge datasets based on a unique identifier (e.g., house ID), creating a single, comprehensive database for analysis.
  
### **Phase 2: Exploratory Data Analysis (EDA)**
- **Correlation Analysis**: Use Seaborn to visualize correlations between house prices and variables such as geographic area, property type, and tenure.
- **Distribution Analysis**: Plot histograms and box plots to understand the distribution of house prices across different regions and property types.
  
### **Phase 3: Statistical Analysis & Forecasting**
- **Co-Variable Analysis**: Perform multivariate analysis to assess which factors (beyond location) influence house prices.
- **Price Forecasting**: Implement machine learning techniques to forecast future house prices based on historical data. Possible algorithms include **linear regression** and **time series analysis**.

### **Phase 4: Data Visualization**
- **Power BI**: Create interactive dashboards to allow dynamic exploration of the data by end users, making it easier to identify trends and correlations.
- **Seaborn/Matplotlib**: Generate publication-ready visualizations to summarize key findings.

---

## **Conclusion**

This project will provide a comprehensive analysis of house price trends over time in England and Wales, uncovering important insights into regional price variations, co-variables that influence house prices, and forecasting future price trends. By leveraging a modern technology stack that includes **PySpark**, **Polars**, and **Power BI**, the project showcases skills in both **data analysis** and **data engineering**. 

This multi-faceted approach highlights your competence in handling large datasets, performing statistical analysis, and presenting insights in a visually engaging manner.
