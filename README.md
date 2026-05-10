# 🌍 World Happiness Report — Exploratory Data Analysis

A complete end-to-end Data Analysis project on the **World Happiness Report dataset** — covering data loading, cleaning, exploration, statistical analysis, correlation study, and rich visualizations to uncover what factors make countries happier.

---

## 📌 Project Overview

This project analyzes the World Happiness Report data for **158 countries** across **12 key happiness indicators** — including GDP, Family, Health, Freedom, Trust in Government, and Generosity — to identify patterns, correlations, and regional trends in global happiness.

---

## 🚀 Analysis Performed

| Step | Description |
|---|---|
| Data Loading | Loaded CSV dataset using Pandas |
| Data Exploration | Shape, head, tail, column names, data types |
| Data Cleaning | Null value check, missing data handling |
| Descriptive Statistics | Mean, std, min, max, quartiles for all columns |
| Correlation Analysis | Heatmap to find relationships between variables |
| Top/Bottom Countries | Happiest and least happy countries identified |
| Regional Analysis | Happiness score comparison by world region |
| Outlier Detection | Boxplot analysis on Health (Life Expectancy) |
| Data Visualization | Bar, scatter, heatmap, histogram, boxplot charts |

---

## 📊 Dataset Details

| Property | Value |
|---|---|
| Source | World Happiness Report |
| Rows | 158 countries |
| Columns | 12 features |
| Key Columns | Country, Region, Happiness Score, GDP, Family, Health, Freedom, Trust, Generosity |

---

## 🛠️ Tech Stack

- **Language:** Python 3.13
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Concepts:** EDA, Data Cleaning, Statistical Analysis, Correlation, Data Visualization
- **Tool:** Jupyter Notebook

---

## 📁 Project Structure

```
python-capstone-project/
│
├── Final_Project.ipynb              # Main Jupyter Notebook
├── world_happiness_report.csv       # Dataset
└── README.md                        # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/ravindra-data/python-capstone-project.git
```

2. Install dependencies
```bash
pip install pandas matplotlib seaborn
```

3. Open the notebook
```bash
jupyter notebook Final_Project.ipynb
```

---

## 📸 Dataset Preview

```
       Country          Region  Happiness Rank  Happiness Score  Economy (GDP)
0  Switzerland  Western Europe               1            7.587        1.39651
1      Iceland  Western Europe               2            7.561        1.30232
2      Denmark  Western Europe               3            7.527        1.32548
3       Norway  Western Europe               4            7.522        1.45900
4       Canada   North America               5            7.427        1.32629

Total: 158 rows × 12 columns
```

---

## 🔍 Key Insights

- **Western Europe** dominates the top happiness rankings
- **Economy (GDP per Capita)** has the strongest correlation with Happiness Score
- **Health (Life Expectancy)** and **Family** are also major contributing factors
- **Sub-Saharan Africa** has the lowest average happiness scores
- **Switzerland** ranked #1 with a happiness score of 7.587

---

## 💡 What I Learned

- Loading and exploring real-world datasets using Pandas
- Performing full EDA — shape, info, describe, null checks
- Creating correlation heatmaps to identify key relationships
- Visualizing country and regional comparisons using bar and scatter plots
- Detecting outliers using boxplots with Seaborn
- Drawing meaningful insights from data to tell a data story

---
