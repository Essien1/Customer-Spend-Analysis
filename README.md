#  Marketing Analytics Regression Project

![R](https://img.shields.io/badge/Language-R-276DC3?style=flat&logo=r&logoColor=white)
![RMarkdown](https://img.shields.io/badge/Report-RMarkdown-blue?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat)

---

## 📌 Overview

This project applies multiple regression analysis to a marketing dataset of **5,000 customer records** to identify the key drivers of purchase amount.

The analysis combines **exploratory data analysis, model development, diagnostic testing, and business insights**, following the DAMO 520 assignment structure.

---

## 📊 Dataset

| Property | Detail |
|---|---|
| Observations | 5,000 |
| Variables | 15 |
| Target Variable | `PurchaseAmount` ($7.23 – $167.11) |
| Source | DAMO 520 Course Dataset |

### Key Variables

- **Income** — strongest predictor of spending  
- **WebsiteVisits** — engagement driver  
- SatisfactionScore, EmailOpens, TimeOnSite — tested but not significant  

---

## ⚙️ Methodology

### 1. Exploratory Data Analysis
- Correlation analysis and visualisation (`corrplot`)
- Scatterplots with regression lines (`ggplot2`)
- Boxplots and density plots
- Outlier detection using IQR method

### 2. Model Development

| Model | Description | Adj R² | AIC |
|---|---|---|---|
| Model 1 | Income only | 0.3398 | 42,772.86 |
| Model 2 | Full model (5 predictors) | 0.4226 | 42,106.92 |
| Model 3 | Income × WebsiteVisits | 0.4229 | 42,101.90 |

---

### 3. Diagnostic Testing

- ✅ Linearity (Residual plots)  
- ✅ Normality (Shapiro-Wilk test)  
- ✅ Homoscedasticity (Breusch-Pagan test)  
- ✅ Multicollinearity (VIF)  
- ✅ Influential observations (Cook’s Distance)  

---

