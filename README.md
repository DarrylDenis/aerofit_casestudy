# aerofit_casestudy
Using probability and stats to answer business problems for aerofit


---

# 🏃‍♂️ Aerofit Customer Profiling – Descriptive Analytics & Probability

## 📌 Project Overview

This project focuses on analyzing customer data for **Aerofit**, a fitness equipment company, to understand who buys each type of treadmill and why. The goal is to help the business make **data-driven product recommendations** and build targeted marketing strategies based on customer characteristics.

---

## 🎯 Objective

* Build detailed customer profiles for each treadmill model: **KP281 (entry-level), KP481 (mid-range), KP781 (advanced)**
* Identify how demographic and behavioral features influence product preference
* Calculate **marginal and conditional probabilities** to support marketing decisions
* Deliver actionable insights for **customer segmentation and targeting**

---

## 📂 Dataset Details

The dataset contains data from customers who purchased a treadmill in the last three months:

* `Product Purchased`: KP281, KP481, KP781
* `Age`, `Gender`, `Education`, `MaritalStatus`
* `Usage`: Planned weekly usage
* `Income`: Annual income in USD
* `Fitness`: Self-rated (1 to 5 scale)
* `Miles`: Expected miles per week

---

## 🔍 Key Analysis Performed

* **Data Inspection & Cleaning**: Checked for nulls, outliers (via boxplots & `describe()`), and distribution shapes
* **Visual Exploration**: Analyzed product preference by age, gender, marital status using countplots, histograms, and boxplots
* **Contingency Tables**: Created two-way tables to compute marginal and conditional probabilities
* **Correlation Mapping**: Used heatmaps and pairplots to identify relationships among variables
* **Customer Profiling**: Clustered customers by product preference, fitness levels, income, and usage habits

---

## 📈 Sample Questions Answered

* What type of customers buy each treadmill model?
* Does **age, gender, or income** impact treadmill choice?
* What is the **probability** that a male customer will buy a KP781?
* Which segment is most likely to buy high-end equipment?

---

## ✅ Insights & Recommendations

* **KP281** attracts younger users with moderate fitness levels and lower income
* **KP481** is preferred by middle-aged, fitness-conscious individuals with mid-range incomes
* **KP781** buyers tend to have higher income, higher fitness ratings, and run longer distances weekly
* Gender and marital status show distinct patterns in product preference, useful for **targeted marketing**

---

## 🧰 Tools Used

* Python (Pandas, Matplotlib, Seaborn)
* Descriptive Statistics
* Conditional & Marginal Probability Calculations
* Data Visualization & Exploratory Data Analysis (EDA)

---

This project demonstrates how basic statistics and visual storytelling can provide **clear, data-backed business recommendations**—a practical example of using analytics to support product and marketing decisions.

---

Let me know if you want to add visuals, interactive dashboards, or Jupyter notebook previews!

