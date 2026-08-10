# 🌫️ Indian Air Quality — Exploratory Data Analysis

## 📌 Project Overview

Air pollution is one of the major environmental challenges affecting urban areas in India.

This project performs an **Exploratory Data Analysis (EDA)** of daily air-quality observations collected across Indian cities. The analysis focuses on understanding **AQI trends, city-level pollution patterns, pollutant concentrations, seasonal variations, and extreme pollution events**.

The project demonstrates how Python-based data analysis can transform raw environmental data into meaningful insights for better monitoring and decision-making.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze air-quality trends over time.
* Compare AQI levels across Indian cities.
* Identify major pollutants and their concentrations.
* Examine monthly and seasonal pollution patterns.
* Analyze the distribution of AQI categories.
* Identify cities experiencing extreme AQI levels.
* Generate actionable environmental insights and recommendations.

---

## 📊 Dataset

**Dataset:** Air Quality Data in India (2015–2020)

**Source:** Kaggle / Central Pollution Control Board (CPCB)

The analysis uses the `city_day.csv` file containing daily air-quality observations.

### Dataset Dimensions

* **Rows:** 29,531
* **Columns:** 16
* **Cities:** Multiple Indian cities
* **Time Period:** 2015–2020

### Key Variables

| Variable   | Description                         |
| ---------- | ----------------------------------- |
| City       | City where observation was recorded |
| Date       | Date of observation                 |
| PM2.5      | Fine particulate matter             |
| PM10       | Coarse particulate matter           |
| NO         | Nitric oxide                        |
| NO2        | Nitrogen dioxide                    |
| NOx        | Nitrogen oxides                     |
| NH3        | Ammonia                             |
| CO         | Carbon monoxide                     |
| SO2        | Sulfur dioxide                      |
| O3         | Ozone                               |
| Benzene    | Benzene concentration               |
| Toluene    | Toluene concentration               |
| Xylene     | Xylene concentration                |
| AQI        | Air Quality Index                   |
| AQI_Bucket | AQI category                        |

---

## 🛠️ Tools & Technologies

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook / Kaggle Notebook**

> This project intentionally uses NumPy, Pandas, and Matplotlib to maintain a simple and transparent analytical workflow.

---

## 🧹 Data Cleaning

The following data preparation steps were performed:

* Inspected dataset structure and data types.
* Converted the `Date` column to datetime format.
* Created `Year` and `Month` features.
* Checked for missing values.
* Checked for duplicate records.
* Examined the availability of AQI observations.
* Preserved available pollutant observations instead of unnecessarily deleting incomplete rows.
* Used available AQI observations for AQI-based analysis.

The dataset contains missing observations for several pollutants, particularly **Xylene**, so pollutant-specific analysis uses the available observations for each variable.

---

# 🔎 Business Questions

The analysis addresses six key questions:

### Q1. How has air quality changed over time?

Analyzed yearly average AQI to identify long-term changes in air quality.

### Q2. Which cities have the highest average AQI?

Compared city-level average AQI to identify areas with consistently poorer air quality.

### Q3. Which pollutants have the highest concentrations?

Compared average concentrations of major pollutants including PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, and Xylene.

### Q4. Which months experience poorer air quality?

Analyzed monthly average AQI to identify seasonal pollution patterns.

### Q5. What is the distribution of AQI categories?

Examined the frequency of different AQI categories to understand overall air-quality conditions.

### Q6. Which cities experience the most extreme AQI levels?

Compared maximum recorded AQI across cities to identify locations experiencing severe pollution events.

---

# 📈 Key Analysis

The project includes visualizations covering:

* 📅 Yearly AQI trends
* 🏙️ Top polluted cities
* 🧪 Average pollutant concentrations
* 🌦️ Monthly AQI patterns
* 🚦 AQI category distribution
* 🚨 Extreme AQI levels by city

---

# 💡 Key Insights

The analysis highlights several important patterns:

* Air quality varies considerably between Indian cities.
* AQI changes across different years and periods.
* Particulate matter, particularly PM2.5 and PM10, represents an important pollution concern.
* Air quality follows noticeable monthly and seasonal patterns.
* AQI categories provide a useful view of the frequency of different pollution conditions.
* Extreme AQI events can reveal pollution problems that may not be visible from average AQI alone.

> Numerical findings are presented directly in the notebook based on the analyzed dataset.

---

# 💡 Recommendations

Based on the analysis:

1. **Prioritize highly polluted cities** for targeted pollution-control initiatives.
2. **Monitor PM2.5 and PM10 closely** due to their importance in urban air pollution.
3. **Strengthen seasonal preparedness** during periods historically associated with higher AQI.
4. **Improve pollution monitoring infrastructure** to reduce missing observations.
5. **Develop stronger alerts for extreme AQI events.**
6. **Investigate local emission sources** such as traffic, industrial activity, construction, and other urban contributors.

---

# 📂 Repository Structure

```text
indian-air-quality-eda/
│
├── README.md
├── indian_air_quality_eda.ipynb
├── data/
│   └── README.md
├── images/
│   ├── yearly_aqi_trend.png
│   ├── top_polluted_cities.png
│   ├── pollutant_analysis.png
│   ├── monthly_aqi.png
│   ├── aqi_categories.png
│   └── extreme_aqi_cities.png
└── .gitignore
```

---

# 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Quality Analysis
     ↓
Data Cleaning
     ↓
Feature Engineering
     ↓
Exploratory Data Analysis
     ↓
Visualizations
     ↓
Business Insights
     ↓
Recommendations
     ↓
Conclusion
```

---

# 🎓 Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis
* Data Cleaning
* Missing Value Analysis
* Descriptive Statistics
* GroupBy Analysis
* Aggregation
* Time-Series Analysis
* Feature Engineering

### Python

* NumPy
* Pandas
* Matplotlib
* Datetime manipulation

### Analytical Skills

* Trend Analysis
* Comparative Analysis
* Environmental Data Analysis
* Business Question Formulation
* Insight Generation
* Data Storytelling

---

# 📚 References

* Kaggle — Air Quality Data in India
* Central Pollution Control Board (CPCB)
* Government of India — National Air Quality Monitoring Programme

### Dataset Source

https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india

---

## 👤 Author

**L Shubham**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Tableau

🔗 GitHub: https://github.com/shubham-lingam

🔗 LinkedIn: https://www.linkedin.com/in/shubham-lingam

---

⭐ If you find this project useful, feel free to explore the repository and notebook.
