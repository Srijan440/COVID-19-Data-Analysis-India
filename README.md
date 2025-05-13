
# 🧪 COVID-19 Data Analysis – India 🇮🇳

---



## 📌 Project Overview

This is a small data analysis project using Python (Pandas, NumPy, Matplotlib, Seaborn) to explore COVID-19 trends in India. The project focuses on understanding cases, deaths, recoveries, and vaccination progress using time-series analysis and visualization.

---

## 📂 Dataset Info

- **Source:** [Our World in Data - COVID Deaths](https://ourworldindata.org/covid-deaths)
- **GitHub Repository:** [COVID-19 Dataset on GitHub](https://github.com/owid/covid-19-data)
- Key columns used:
    - `date`
    - `new_cases`, `total_cases`
    - `new_deaths`, `total_deaths`
    - `people_vaccinated`, `people_fully_vaccinated`

---

## 🧭 Steps Performed

### 🔹 Step 1: Loading the Dataset  
- Used `pd.read_csv()` to load data into `india_df`.

### 🔹 Step 2–5: Data Cleaning & Exploration  
- Checked missing values
- Explored summary statistics (`.info()`, `.describe()`)

### 🔹 Step 6: Total COVID-19 Cases Over Time  
- Line plot of `total_cases` over `date`.

### 🔹 Step 7: Daily New COVID-19 Cases  
- Created a `daily_new_cases` column.
- Plotted trends to highlight peaks/waves.

### 🔹 Step 8: Correlation Heatmap  
- Visualized correlations between total cases, deaths, and vaccination progress.

### 🔹 Step 9–10: Recovery and Death Trends  
- Tracked how total and new deaths evolved over time.

### 🔹 Step 11-12: Vaccination Progress  
- Plotted people vaccinated and fully vaccinated over time.
- Calculated % of Indian population vaccinated.

### 🔹 Step 13: Testing Trends  
- Skipped due to lack of testing data.

### 🔹 Step 14: Conclusion and Insights  
- Vaccination had clear impact on reducing case/death rates.
- Clear spikes in daily cases highlighted key COVID waves.
- Strong correlation between total cases and deaths.

---

## 📈 Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn

---

## 💡 Key Insights

- India vaccinated over 1 billion people, significantly flattening the curve.
- Cases and deaths rose in parallel, especially during major waves.
- Visualization and data analysis help make sense of large-scale public health data.

---


