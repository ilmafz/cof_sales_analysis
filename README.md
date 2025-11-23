# ☕ Coffee Sales Analysis

A comprehensive exploratory analysis of coffee vending machine transactions aimed at identifying product performance, sales patterns, and time-based demand behaviour. The objective is to convert raw operational data into insights that can support decision-making in product planning, inventory management, and customer engagement strategies.

---

## 📌 Project Overview

This project presents a structured analysis of transactional coffee sales data.  
The study focuses on:

- Understanding **which products drive the highest sales**
- Identifying **peak demand hours** and **busy days**
- Evaluating **monthly performance trends**
- Examining **payment behaviour**
- Comparing **product-wise hourly demand profiles**

The notebook demonstrates strong analytical workflow practices, including data cleaning, feature engineering, trend evaluation, and visualisation.

---

## 📂 Dataset Summary

The dataset contains detailed operational records:

- `date` — Date of each transaction  
- `datetime` — Exact timestamp  
- `coffee_name` — Product purchased  
- `money` — Amount paid  
- `cash_type` / `card` — Payment channel information  

From these variables, additional time-based attributes were engineered:

- `hour`  
- `day`  
- `month`  
- `year`

These attributes enable more granular insights into behavioural patterns.

---

## 🧹 Data Processing & Preparation

The preprocessing pipeline includes:

- Handling missing values in the `card` column by imputing `"cash"`  
- Converting `date` and `datetime` into appropriate datetime formats  
- Extracting `hour`, `day`, `month`, and `year` for temporal analysis  
- Standardising fields and validating data consistency  
- Ensuring a clean and analysis-ready structure with Pandas operations  

This structured approach ensures that insights derived from the data are reliable and actionable.

---

## 📊 Key Analytical Findings

### ⭐ Product Performance
- **Americano with Milk** emerges as the strongest performer, indicating consistent customer preference.

### ⏰ Time-Based Demand
- Sales peak during **morning hours (8 AM – 11 AM)**, reflecting typical consumption behaviour.
- Different coffee types exhibit unique hourly demand curves.

### 📅 Monthly Trends
- **May** records the highest monthly sales volume.
- Seasonal patterns suggest potential opportunities for targeted promotions.

### 💳 Payment Insights
- After resolving missing entries, cash payments constitute the majority of transactions.

---

## 📈 Visual Exploration

The analysis includes a comprehensive set of visualisations:

- Daily revenue trend  
- Month-over-month comparison  
- Hourly sales distribution  
- Multi-subplot view of hourly demand segmented by product  
- Product popularity ranking  

All visual outputs were developed using Matplotlib and structured for interpretability.

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🎯 Conclusion

This analysis converts raw transactional data into clear, actionable insights on customer behaviour and product performance.  
The findings can assist business stakeholders in:

- Optimizing product availability  
- Planning inventory more strategically  
- Adjusting offerings based on peak demand hours  
- Enhancing promotional decisions  

The project demonstrates analytical rigor, clean data processing, and effective insight communication — key competencies for data and business analytics roles.

---
