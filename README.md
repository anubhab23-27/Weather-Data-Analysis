# 🌦️ Weather Data Analysis Project

## 📌 Overview
This project analyzes historical weather data using Python to understand patterns, trends, and relationships between different weather parameters.

The analysis focuses on:
- 🌡️ Temperature variations over time  
- 💧 Humidity patterns  
- 🌬️ Wind speed and direction  
- 👁️ Visibility and atmospheric conditions  
- 📊 Relationships between weather features  

---

## 📊 Dataset
- File: `weatherHistory.csv`

The dataset includes:
- Date and time information  
- Weather summary and precipitation type  
- Temperature and apparent temperature  
- Humidity levels  
- Wind speed and wind bearing  
- Visibility and pressure  

- Total Records: **96,453**  
- Total Features: **12 columns**  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure
```bash
weather-analysis/
│── weather_analysis.ipynb
│── weatherHistory.csv
│── README.md
│── .gitignore
```
---

## 🔍 Key Analysis

### Dataset Overview
- Checked dataset shape, columns, and data types
- Identified missing values in dataset

➡️ Found missing values in Precip Type column

---

### Data Cleaning
- Handled missing values using mode 

➡️ Dataset cleaned successfully with no missing values

---

### Statistical Analysis

Calculated key statistics:

- Mean, Median, Mode
- Standard Deviation & Variance
- Minimum & Maximum
- Quartiles (Q1, Q2, Q3)
- Skewness & Kurtosis

➡️ Helps understand data distribution and variability

---


## 📊 Visualizations
- Histogram → Temperature distribution
- Boxplot → Humidity distribution & outliers
- Scatter plot → Temperature vs Humidity

➡️ The histogram shows temperature follows a near-normal distribution <br>
➡️ The scatter plot shows inverse relation between temperature and humidity
---
### Trend Analysis
- Analyzed temperature trends over time
- Analyzed humidity trends over time

➡️ Line charts (page 9) show clear seasonal variations in temperature <br>
➡️ Humidity fluctuates throughout the year
---
### Correlation Analysis
- Generated heatmap to understand feature relationships

➡️ Strong correlation between:

- Temperature and Apparent Temperature (~0.99)

➡️ Negative correlation between:

- Temperature and Humidity (~ -0.63)

➡️ Heatmap visualization highlights relationships clearly
---

## 🧠 Key Insights
- Temperature shows clear seasonal patterns
-  Humidity is inversely related to temperature
- Strong correlation between temperature and apparent temperature
- Some features like Loud Cover have no variation and were removed

---

## ⚠️ Limitations
- Dataset may not represent all global weather conditions
- External factors not considered:
    - Climate change
    - Geographic differences
    - Sudden weather events

---

## 🎯 Conclusion
Weather patterns show strong seasonal trends, with temperature and humidity having an inverse relationship. Correlation analysis reveals key dependencies between variables, helping in better understanding of atmospheric behavior and prediction models.

---

## 🚀 How to Run

Install dependencies:
```bash
pip install pandas matplotlib seaborn
```
Run Jupyter Notebook:
```bash
jupyter notebook
```
Open:
```bash
weather_analysis.ipynb
```

---
## 👨‍💻 Author

**Anubhab Ghosh**

B.Tech CSE (AI & ML)
Interested in Web Development, AI, and Data Science.

GitHub:
https://github.com/anubhab23-27

---

⭐ If you like this project, consider giving it a star!
