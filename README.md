# 🌍 World Population Data Analysis - EDA
### 📌 Overview
This project explores **global population trends** using **Exploratory Data Analysis (EDA)**.  
We analyze **population growth, density, and regional trends** from **1970 to 2022**.

### 🔍 Dataset Details
- **Rows & Columns:** `234 rows × 17 columns`
- **Key Features:** Population by year, continent, growth rate, density.
- **Missing Values:** Some gaps in older population data.

### 🛠 Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook for interactive analysis

---

## 📊 **Key Insights**
- 🌎 **Most Populous Countries (2022):** China 🇨🇳, India 🇮🇳, USA 🇺🇸, Indonesia 🇮🇩, Pakistan 🇵🇰.
- 📈 **Fastest Growing Continent:** **Africa** has the highest growth rate.
- 📊 **Correlation:** Strong correlation between past and present population data.

---

## 📈 **Visualizations**
### **1️⃣ Population Growth by Continent**
```python
df2.plot(figsize=(20,7))
