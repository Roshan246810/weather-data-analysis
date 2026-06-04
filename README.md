# 🌤️ Weather Data Analysis Project using Python & Pandas

A comprehensive Exploratory Data Analysis (EDA) on a Weather Dataset to find patterns, clean missing records, and filter weather anomalies using **Python** and **Pandas**.

---

## 📊 Project Overview
This project focuses on analyzing a time-series weather dataset that contains per-hour information about various weather parameters such as Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Weather Conditions.

## 🛠️ Tech Stack & Libraries Used
- **Language:** Python 🐍
- **Library:** Pandas (Data Manipulation & Exploration)
- **Environment:** Jupyter Notebook / VS Code

---

## 🔍 Key Highlights & Solved Problems
The project demonstrates core Data Analyst skills by solving **15 specific analytical business questions**, including:
1. **Data Exploration & Inspection:** Using `.head()`, `.shape`, `.index`, `.columns`, and `.dtypes`.
2. **Data Cleaning:** Finding and treating null values using `.isnull().sum()` and renaming variables for consistency.
3. **Filtering & Slicing:** Extracting specific instances (e.g., finding instances when weather was exactly 'Clear' or 'Snow', or when Wind Speed was above 24 km/h).
4. **Statistical Aggregation:** Utilizing `.groupby()` along with `.mean()`, `.std()`, and `.var()` to get summary statistics against each Weather Condition.

---

## 📁 Repository Structure
```text
├── 1. Weather Data.csv              # Raw Weather Dataset
├── Python Data Analysis Project.ipynb # Core Jupyter Notebook with source code
└── README.md                        # Project documentation (This file)
