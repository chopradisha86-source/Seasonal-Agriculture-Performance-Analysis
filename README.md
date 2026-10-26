# 🌾 Seasonal Agricultural Data Analysis & Risk Auditing

An advanced exploratory data analysis (EDA), statistical inferencing, and operational risk auditing framework built to analyze seasonal crop performance, environmental impacts, and financial viability across agricultural regions.

---

## 📌 Project Overview

This project provides a quantitative evaluation of agricultural productivity, resource consumption efficiency, and farm-level profitability across diverse seasonal cycles. By leveraging parametric and non-parametric statistical testing alongside multivariate visualizations, the pipeline identifies high-yielding crop-season configurations, detects non-performing/high-cost operational anomalies, and offers actionable strategies for resource allocation.

---

## 🔑 Key Features

* dynamic Data Schema Resolution: Automated column detection for seamless handling of dynamic header formats.
* Domain Feature Engineering: Generates domain metrics including Profit_Margin_Percent, Cost_per_Unit_Area, Revenue_per_Unit_Area, Total_Input_Chemicals_kg, and Chemical_Cost_Intensity.
* 8 Analytical Visual Dashboards:
  - Seasonal yield and profit margin boxplot distributions.
  - Environmental profiles (Rainfall, Temperature, Humidity).
  - Input intensity violin plots (Fertilizers & Pesticides).
  - Crop x Season yield interaction heatmaps.
  - Regional yield performance across states.
  - Financial expenditure vs. revenue scatter analysis with breakeven metrics.
  - Chemical input yield response regression trends.
  - Multivariate feature correlation matrix.
* Inferential Statistical Testing:
  - One-Way ANOVA & SciPy Tukey HSD Post-Hoc Tests (Yield vs. Season).
  - Kruskal Wallis Non-Parametric Variance Analysis.
  - Chi-Square Test of Independence (Season vs. Profitability Status).
* Operational Risk Auditing: Outlier and anomaly detection mapping high-expenditure farms operating at net losses.

---

## 📂 Repository Structure

Seasonal-Agriculture-Performance-Analysis/
├── .gitignore
├── README.md
└── main_analysis.ipynb

---

## 🚀 Getting Started

### 1. Prerequisites

Ensure you have Python 3.8+ installed along with the required analytical libraries:

pip install numpy pandas matplotlib seaborn scipy

### 2. Execution

1. Clone the repository:
   git clone https://github.com/chopradisha86-source/Seasonal-Agriculture-Performance-Analysis.git
   cd Seasonal-Agriculture-Performance-Analysis

2. Launch Jupyter Notebook or VS Code:
   jupyter notebook main_analysis.ipynb

3. Run all cells in main_analysis.ipynb to execute preprocessing, generate dashboards, and compute statistical outputs.

---

## 📊 Summary of Findings & Strategic Policy Recommendations

1. Dynamic Crop-Season Alignment: Optimizing crop selection based on seasonal interaction profiles significantly reduces yield variance across states.
2. Resource Optimization: Regression analysis indicates diminishing yield returns on chemical inputs beyond specific thresholds; implementing targeted soil health guidelines lowers cost overheads without sacrificing output.
3. Targeted Risk Mitigation: Identifying high-cost, negative-profit farm clusters enables localized micro-irrigation interventions and targeted agricultural extension services.
