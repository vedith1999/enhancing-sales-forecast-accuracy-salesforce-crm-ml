# enhancing-sales-forecast-accuracy-salesforce-crm-ml
MBA Thesis report on ENHANCING SALES FORECAST ACCURACY USING SALESFORCE CRM AND PREDICTIVE ANALYTICS

# 📊 Enhancing Sales Forecast Accuracy using Salesforce CRM and Predictive Analytics

This repository contains the code, sample data, and analytical workflow developed for the thesis:

> **Enhancing Sales Forecast Accuracy using Salesforce CRM and Predictive Analytics**  
> by Jupaka Vedith Kumar  
> Supervisor: Liverpool John Moores University (LJMU) in collaboration with upGrad  
> Year: 2025  

---

## 🎯 Project Overview

Accurate sales forecasting is central to organizational decision-making and resource planning.  
This project evaluates how **predictive analytics and machine-learning models** (Random Forest, XGBoost, LSTM) can improve forecast accuracy within **Salesforce CRM** compared to traditional stage-weighted methods.

The study uses anonymised Salesforce opportunity data combined with macro-level business indicators to train, validate, and benchmark forecasting models.  
Analyses were conducted using **Google Colab (Python)** and **Microsoft Excel (Data Analysis ToolPak)**.

---

## 🧠 Research Objectives

1. **Critically assess** limitations of existing Salesforce forecasting processes at Tech Manufacturing Solutions Ltd. (TMSL) — focusing on data, procedural, and behavioural inefficiencies.  
2. **Develop, train, and validate** machine-learning models (Random Forest, XGBoost, LSTM) using historical CRM and macroeconomic data.  
3. **Benchmark** predictive accuracy against traditional stage-weighted forecasting methods.  
4. **Analyse organisational perceptions** and acceptance of AI-driven forecasting using UTAUT constructs.  
5. **Recommend** ethically grounded, context-specific strategies for sustainable adoption of predictive analytics in CRM operations.

---

## 🧩 Repository Structure
│
├── notebooks/
│ └── 01_model_build_colab.ipynb # Google Colab notebook for model development
│
├── excel/
│ └── working_sales_forecast.xlsx # Excel working file for EDA and comparisons
│
├── data/
│ ├── raw/
│ │ ├── Sales Opportunities Win Loss Data Sample Dataset # 100-row anonymised sample dataset
│ └── processed/ # clean/feature-engineered data (created by notebook)
│
├── src/
│ ├── features/ # feature engineering scripts
│ ├── models/ # model training / evaluation scripts
│ └── utils/ # helper functions
│
├── reports/
│ └── figs/ # visualisations and charts
│
├── requirements.txt # Python dependencies
├── .gitignore
├── LICENSE (MIT)
└── README.md

## 🧮 Data Description

**Dataset Fields**
| Variable | Description |
|-----------|-------------|
| Opportunity ID | Unique identifier for each sales opportunity |
| Technology Primary | Product / technology type |
| City | Client location |
| B2B Sales Medium | Channel of engagement |
| Sales Velocity | Average time to close opportunity |
| Sales Stage Iterations | Number of stage changes |
| Opportunity Size (USD) | Deal size |
| Client Revenue Sizing | Client’s annual revenue category |
| Client Employee Sizing | Client’s workforce size category |
| Business from Client Last Year | Historical sales |
| Compete Intel | Competitive intensity indicator |
| Opportunity Sizing | Overall opportunity potential |

---

## 📂 Data Access

A small **anonymised sample dataset** is included for demonstration.  
The **full dataset** and **complete Excel workbook** (≈ 35 MB) are hosted securely on Google Drive:

🔗 [**Access full dataset and Excel workbook (Google Drive)**](https://docs.google.com/spreadsheets/d/1MYBS2WHOkFKbVrrNuTJ_ZjNoGTTUb5_A/edit?usp=drive_link&ouid=111143816470989320664&rtpof=true&sd=true)

> 📌 *Note:* Access is restricted to reviewers and authorised academic personnel.  
> All sensitive client identifiers have been anonymised or aggregated.

---

## 🧰 Tools and Environment

| Tool | Purpose |
|------|----------|
| **Google Colab (Python 3.10)** | Model development and validation |
| **Microsoft Excel 2021** | Exploratory analysis and baseline forecasting |
| **Python Libraries:** pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, keras | Data processing, modelling, and visualisation |
| **Excel Add-in:** Analysis ToolPak | Regression and correlation analysis |

To reproduce the environment:
```bash
pip install -r requirements.txt
