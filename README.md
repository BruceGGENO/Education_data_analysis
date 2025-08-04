
# SDG 4: Quality Education Analytics

This project explores Sustainable Development Goal 4: Quality Education using a dataset from a global education database. It includes Python-based analytics and a Power BI dashboard to uncover trends, clusters, and insights in education metrics across countries.

---

## 📂 Project Structure

```
📁 SDG-Education-Analytics/
│
├── data/
│   └── cleaned_education_data.csv
├── notebooks/
│   └── education_analysis.ipynb
├── powerbi/
│   └── education_dashboard.pbix  # (To be added)
├── README.md
```

---

## 🎯 Objective

To analyze and visualize education indicators across countries to:
- Identify trends and disparities
- Cluster similar countries based on education profiles
- Support data-driven education policy recommendations

---

## 📊 Dataset Overview

- **Source:** Publicly available dataset on SDG 4
- **Data Type:** Structured CSV
- **Rows:** Varies by year and indicator
- **Columns:** Location, Year, Indicator, Value, Unit

---

## 🛠️ Tools Used

- **Python** (pandas, seaborn, sklearn, matplotlib)
- **Power BI** (dashboard visualizations)
- **Jupyter Notebook** (analysis documentation)

---

## 🔍 Key Steps in Analysis

1. **Data Cleaning**
   - Removed duplicates
   - Handled missing values
   - Converted types for analysis

2. **Exploratory Data Analysis (EDA)**
   - Distribution of indicators by country
   - Time series analysis (e.g., out-of-school rates)

3. **Clustering**
   - KMeans clustering of countries based on average indicators
   - Visualized in 2D using PCA

4. **Innovation**
   - Anomaly detection using Isolation Forest to flag outlier countries

---

## 📈 Power BI Dashboard (To Be Added)

**Features:**
- Line chart: Trends in dropout and literacy rates
- Bar chart: Indicator comparisons across countries
- Map visual: Education performance by region
- Slicers for year, location, and indicator
- KPI cards and drilldowns for detail

---

## 🚀 How to Use

1. Open `notebooks/education_analysis.ipynb` to explore the Python analysis.
2. Use the cleaned dataset in `data/cleaned_education_data.csv`.
3. Open the Power BI file (to be added) in Power BI Desktop.

---

## 📌 Results & Insights

- Wide gaps exist in education quality between regions.
- Certain countries cluster together in similar educational performance.
- A few countries stand out as anomalies worth further investigation.

---

## 📌 Future Work

- Integrate more indicators (e.g., internet access in schools)
- Apply time-series forecasting (e.g., ARIMA or LSTM)
- Link to other SDGs for cross-domain insights

---

## 🙌 Acknowledgements

Instructor: *Eric Maniraguha*  
Course: *Introduction to Big Data Analytics – INSY 8413*  
Academic Year: *2024–2025, SEM III*
