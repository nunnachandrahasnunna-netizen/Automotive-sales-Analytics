# 🚗 Four Wheeler Automotive India — Sales & Performance Dataset

![India Automotive](https://img.shields.io/badge/Domain-Automotive-blue?style=flat-square)
![Records](https://img.shields.io/badge/Records-100-green?style=flat-square)
![Years](https://img.shields.io/badge/Years-2015--2025-orange?style=flat-square)
![Brands](https://img.shields.io/badge/Brands-5-red?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

A comprehensive dataset tracking four-wheeler automotive sales, revenue, and performance across **5 major Indian car brands**, **5 cities**, and **11 years (2015–2025)**. Ideal for sales analytics, market research, EDA, and business intelligence dashboards.

---

## 📁 File Structure

```
four_wheeler_automotive_india.xlsx
├── Automotive Data     ← Raw transactional data (100 rows × 16 columns)
├── Pivot data          ← Pre-aggregated pivot summaries
├── Dash Board          ← Visualization dashboard (interactive slicers)
└── Sheet1              ← Supplementary/reference data
```

---

## 📊 Dataset Overview

| Attribute        | Detail                                              |
|------------------|-----------------------------------------------------|
| **Total Records**    | 100                                             |
| **Columns**          | 16                                              |
| **Time Span**        | 2015 – 2025                                     |
| **Brands Covered**   | Tata, Maruti Suzuki, Hyundai, Mahindra, Toyota  |
| **Cities**           | Hyderabad, Chennai, Delhi, Mumbai, Bangalore    |
| **Fuel Types**       | Diesel, Electric, Petrol, CNG                   |
| **Transmission**     | Automatic (56%), Manual (44%)                   |

---

## 🗂️ Column Reference

| Column            | Type    | Description                              |
|-------------------|---------|------------------------------------------|
| `Car_ID`          | int     | Unique identifier for each record        |
| `Year`            | int     | Sales year (2015–2025)                   |
| `Brand`           | string  | Car manufacturer                         |
| `Model`           | string  | Car model name                           |
| `Fuel_Type`       | string  | Fuel type (Petrol/Diesel/CNG/Electric)   |
| `Transmission`    | string  | Gearbox type (Manual/Automatic)          |
| `Engine_CC`       | int     | Engine displacement in cubic centimetres |
| `Mileage_kmpl`    | float   | Fuel efficiency (km per litre)           |
| `City`            | string  | City where sale was recorded             |
| `Price_INR`       | int     | Vehicle price in Indian Rupees           |
| `Sales_Units`     | int     | Number of units sold                     |
| `Revenue`         | int     | Total revenue (Price × Sales_Units)      |
| `Cost`            | float   | Total cost                               |
| `Profit`          | float   | Net profit (Revenue − Cost)              |
| `Salesman names`  | string  | Salesperson responsible for the sale     |
| `Customer Rating` | float   | Customer satisfaction score (4.1 – 4.9) |

---

## 📈 Key Insights

### 🏆 Brand Performance

| Brand         | Revenue (₹)        | Profit (₹)        | Avg Price (₹) | Avg Rating |
|---------------|--------------------|-------------------|----------------|------------|
| Tata          | ₹1,300.1 Cr        | ₹260.0 Cr         | ₹17.87 L       | 4.58       |
| Maruti Suzuki | ₹975.0 Cr          | ₹195.0 Cr         | ₹16.22 L       | 4.58       |
| Hyundai       | ₹854.2 Cr          | ₹170.8 Cr         | ₹15.73 L       | 4.50       |
| Toyota        | ₹514.5 Cr          | ₹102.9 Cr         | ₹19.51 L       | 4.59       |
| Mahindra      | ₹476.5 Cr          | ₹95.3 Cr          | ₹14.02 L       | 4.50       |

> **Profit margin is a uniform 20% across all brands**, indicating consistent pricing strategy in the dataset.

---

### 🚘 Top Models by Sales Units

| Rank | Model   | Sales Units |
|------|---------|-------------|
| 1    | Altroz  | 24,769      |
| 2    | Harrier | 23,490      |
| 3    | Swift   | 21,031      |
| 4    | Venue   | 19,556      |
| 5    | Brezza  | 15,344      |
| 6    | Nexon   | 15,111      |
| 7    | Scorpio | 14,172      |
| 8    | XUV700  | 13,669      |
| 9    | i20     | 12,803      |
| 10   | Verna   | 11,612      |

---

### 🏙️ Revenue by City

| City      | Revenue (₹)   | Records |
|-----------|----------------|---------|
| Hyderabad | ₹1,040.9 Cr   | 25      |
| Chennai   | ₹1,023.7 Cr   | 24      |
| Delhi     | ₹815.3 Cr     | 21      |
| Mumbai    | ₹655.3 Cr     | 14      |
| Bangalore | ₹585.2 Cr     | 16      |

---

### ⛽ Fuel Type Distribution & Mileage

| Fuel Type | Count | Share | Avg Mileage (kmpl) |
|-----------|-------|-------|---------------------|
| Diesel    | 27    | 27%   | 16.22               |
| Electric  | 27    | 27%   | 17.60               |
| Petrol    | 23    | 23%   | 17.57               |
| CNG       | 23    | 23%   | 17.52               |

---

### 📅 Sales Trend by Year

```
Year  │ Sales Units
──────┼──────────────────────────────────────────────
2015  │ 21,455   ████████████
2016  │ 25,507   ██████████████
2017  │ 31,532   █████████████████
2018  │ 23,019   █████████████
2019  │ 18,197   ██████████
2020  │ 13,936   ████████        ← COVID-19 dip
2021  │ 23,334   █████████████
2022  │ 26,915   ███████████████
2023  │  9,620   █████           ← Low sample
2024  │ 20,186   ███████████
2025  │ 35,098   ███████████████████ ← Peak
```

---

### 🧑‍💼 Top Salespeople by Revenue

| Rank | Salesman     | Revenue (₹) |
|------|--------------|-------------|
| 1    | Priya R.     | ₹422.0 Cr   |
| 2    | Vikram P.    | ₹341.7 Cr   |
| 3    | Suman D.     | ₹305.6 Cr   |
| 4    | Suresh K.    | ₹292.1 Cr   |
| 5    | Deepa G.     | ₹281.3 Cr   |

---

### ⚙️ Engine & Price Statistics

| Metric              | Engine CC | Price (INR)  |
|---------------------|-----------|--------------|
| **Mean**            | 1,860 cc  | ₹16.62 L     |
| **Median**          | 1,836 cc  | ₹15.59 L     |
| **Min**             | 825 cc    | ₹5.03 L      |
| **Max**             | 2,982 cc  | ₹29.71 L     |
| **Std Dev**         | 625 cc    | ₹7.38 L      |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas openpyxl matplotlib seaborn
```

### Load the Data

```python
import pandas as pd

df = pd.read_excel('four_wheeler_automotive_india.xlsx', sheet_name='Automotive Data')
print(df.shape)      # (100, 16)
print(df.head())
```

### Quick EDA

```python
# Revenue by brand
df.groupby('Brand')['Revenue'].sum().sort_values(ascending=False)

# Sales trend over years
df.groupby('Year')['Sales_Units'].sum().plot(kind='line', title='Sales Trend')

# Fuel type distribution
df['Fuel_Type'].value_counts().plot(kind='pie', autopct='%1.1f%%')

# Correlation heatmap
import seaborn as sns
numeric_cols = ['Price_INR', 'Sales_Units', 'Revenue', 'Profit', 'Mileage_kmpl', 'Engine_CC']
sns.heatmap(df[numeric_cols].corr(), annot=True, cmap='coolwarm')
```

---

## 💡 Potential Use Cases

- 📊 **Sales Dashboard** — Build Power BI / Tableau / Excel dashboards
- 📉 **Time-Series Analysis** — Study annual sales trends and seasonality
- 🤖 **Machine Learning** — Predict sales units or customer ratings
- 🗺️ **Geo Analysis** — Compare city-wise automotive demand
- 🏷️ **Pricing Strategy** — Analyse price-to-sales and price-to-rating relationships
- 🧪 **EDA Practice** — Great beginner-to-intermediate analytics project dataset

---

## 📌 Notes

- All monetary values are in **Indian Rupees (INR)**
- The profit margin is a consistent **20%** across all entries
- `Unnamed: 16` column is mostly empty; `Unnamed: 17` contains summary statistics
- The dataset covers **19 unique car models** across all brands
- `Customer Rating` ranges from **4.1 to 4.9** (out of 5)

---

## 📜 License

This dataset is provided for educational and analytical purposes under the [MIT License](LICENSE).

---

*Data covers Indian four-wheeler automotive market | 2015–2025 | 5 brands | 5 cities*
