# Atliqo Bank – Credit Card Analysis (Phase 1)

This notebook focuses on analyzing customer transaction and credit profile data for **Atliqo Bank**. The goal is to identify the best target group for launching a new credit card based on behavior, platform usage, product categories, and credit scores.

## File Included
- `phase_1_atliqo_bank.ipynb` → Main notebook with full analysis, visualizations, and conclusions

## Tools Used
- Python
- Jupyter Notebook
- Pandas, Seaborn, Matplotlib, MySQL Connector

## Outcome
Target customer group identified:
- Age: 18-25 years

# 🏦 AtliQo Bank Credit Card Project – Phase 2

## 📌 Project Overview

This project is part of a larger initiative by **AtliQo Bank** to improve customer engagement and financial inclusion through data-driven strategies. In **Phase 2**, the focus is on **A/B testing a new credit card offering** targeted at the **18–25 age group**, an underutilized demographic in terms of credit card usage.

---

## 🎯 Objectives

- Understand the financial behavior of 18–25 year-old customers.
- Design and implement an A/B test for a newly launched credit card.
- Measure the impact of the campaign on average transaction amounts.
- Validate statistical significance through hypothesis testing.

---

## 📊 Key Insights

- **~25%** of customers are aged 18–25.
- This group has **lower average income (< $50K)** and limited credit history.
- Top spending categories:  
  - 📱 Electronics  
  - 👗 Fashion & Apparel  
  - 🧴 Beauty & Personal Care

---

## 🧪 A/B Testing Strategy

- **Test Group:** 100 customers aged 18–25  
- **Control Group:** 40 separate customers in same age group  
- **Campaign Duration:** 2 months (Sept–Nov)  
- **KPI:** Average daily transaction amount using credit card  

The **test group** received the new card offer, while the **control group** did not.

---

## 📐 Statistical Methods

- **Power Analysis:** Used to determine appropriate sample size based on effect size (0.4).
- **Two-Sample Z-Test:**  
  - Hypotheses:  
    - *H₀ (Null)*: No difference in average transaction amount.  
    - *H₁ (Alt)*: Test group has higher average transaction amount.  
  - Result: Statistically significant difference found  
  - **p-value < 0.05** → Reject the null hypothesis  

This project is for educational and portfolio purposes.  
Feel free to reference or build upon it with credit.



