# Customer Spending Analysis (Regression Model)

## 📌 Project Overview
This project analyzes customer purchasing behavior using multiple regression models. The goal is to identify the key factors that drive **Purchase Amount** and translate statistical findings into meaningful business and marketing insights.

The analysis is based on a dataset of 5,000 customers, focusing on how **income and engagement metrics** influence spending.

---

## 🎯 Objectives
- Identify the most important predictors of customer spending
- Compare multiple regression models
- Evaluate model assumptions and performance
- Translate results into actionable marketing strategies

---

## 📊 Dataset
The dataset contains 5,000 customer observations with variables including:
- Income
- WebsiteVisits
- SatisfactionScore
- EmailOpens
- TimeOnSite
- PurchaseAmount (target variable)

---

## ⚙️ Methodology
1. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Scatterplots, boxplots, and density plots
   - Outlier detection

2. **Model Development**
   - Model 1: Income only (baseline)
   - Model 2: Full model (all predictors)
   - Model 3: Interaction model (Income × WebsiteVisits)

3. **Model Evaluation**
   - R², Adjusted R², and AIC comparison
   - Statistical significance testing

4. **Diagnostic Testing**
   - Linearity (Residual plots)
   - Normality (Q-Q plot, Shapiro-Wilk test)
   - Homoscedasticity (Breusch-Pagan test)
   - Multicollinearity (VIF)
   - Influence (Cook’s Distance)

---

## 🔑 Key Findings
- **Income is the strongest predictor** of customer spending
- **WebsiteVisits significantly increases spending**
- SatisfactionScore, EmailOpens, and TimeOnSite show **no meaningful impact**
- Customer spending is driven by:
  - Financial capacity
  - Engagement frequency

---

## 💡 Business Insights
- High-income customers spend significantly more → prioritize premium targeting
- Increasing website visits directly improves revenue
- Email engagement alone does **not** drive purchase value

---

## 🚀 Recommendations
- Segment customers based on income
- Invest in strategies that increase repeat website visits
- Shift email marketing focus from opens → site visits

---

## ⚠️ Limitations
- Model explains ~42% of variance in spending
- Data may lack key variables (e.g., purchase history, product type)
- Results are correlational, not causal

---

## 🔮 Future Improvements
- Add behavioral variables (RFM, customer tenure)
- Test non-linear models (GAM)
- Apply machine learning models (Random Forest, XGBoost)
- Use cross-validation for stronger generalization

---

## 🛠️ Tools & Libraries
- R
- readxl
- ggplot2
- dplyr
- corrplot
- car (VIF)
- lmtest (Breusch-Pagan)

---

## 📂 Project Structure# Customer-Spend-Analysis
Data-driven regression analysis uncovering how income and website engagement influence customer spending
