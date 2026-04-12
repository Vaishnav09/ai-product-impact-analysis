# AI Product Impact Analysis

## Overview
This project analyzes how AI features influence user behavior, adoption, revenue, and retention. The goal is to evaluate whether AI usage translates into measurable business value and identify opportunities to improve product performance.

This work reflects a real-world product analytics approach, combining user segmentation, behavioral analysis, and revenue insights to drive decision-making.

---

## Problem Statement
Organizations invest heavily in AI features but often lack clarity on:

- Are users actually deriving value from AI?
- Does AI improve retention or just initial engagement?
- Which user segments contribute the most revenue?
- Where do users drop off in the adoption journey?

This project answers these questions using structured data analysis and business-focused metrics.

---

## Key Insights

- Users with low AI engagement show higher likelihood of churn  
- Repeat AI usage is strongly correlated with retention  
- AI adoption drives higher revenue contribution in premium tiers  
- Significant drop-offs exist between initial and repeat usage  

---

## Executive Dashboard

The analysis includes an executive-level dashboard tracking:

- AI vs Non-AI user distribution  
- Adoption rate by plan tier  
- Monthly Recurring Revenue (MRR) contribution  
- User segmentation (Heavy, Light, Non-users)  
- Engagement and repeat usage trends  

---

## Approach

### Data Preparation
- Cleaned and standardized raw usage and subscription data  
- Handled missing values and ensured consistency  

### Exploratory Data Analysis
- Analyzed user behavior patterns  
- Compared AI vs non-AI users  
- Evaluated usage frequency and engagement  

### Feature Engineering
- Segmented users into:
  - Heavy Users  
  - Light Repeat Users  
  - Non-AI Users  
- Created engagement and duration metrics  

### Metrics and Analysis
- Adoption Rate  
- Monthly Recurring Revenue (MRR)  
- Repeat Usage Rate  
- Churn Indicators  

### Visualization
- Built charts to analyze trends across segments and plan tiers  
- Designed outputs for business stakeholders  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
- Git and GitHub  

---

## Repository Structure

ai-product-impact-analysis/  
│── data/                  # Raw and processed datasets  
│── notebooks/             # Analysis notebooks  
│── visuals/               # Charts and dashboard outputs  
│── README.md  

---

## Business Recommendations

- Convert light users into repeat users through better onboarding  
- Improve AI feature discoverability and usability  
- Focus on high-revenue segments already adopting AI  
- Introduce product nudges to encourage repeat usage  

---

## Future Improvements

- Build predictive churn models  
- Add cohort-based retention analysis  
- Automate data pipelines (dbt / Airflow style)  
- Deploy dashboards using BI tools (Power BI / Tableau)  

---

## How to Run

```bash
git clone https://github.com/Vaishnav09/ai-product-impact-analysis.git
cd ai-product-impact-analysis
pip install -r requirements.txt
