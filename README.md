# 🚖 Maximizing Driver Revenue Using Payment Type and Fare Analysis

## Project Overview

This project analyzes ride-hailing data to understand how **fare amounts vary across different payment types** (Card, Cash, Flex). The goal is to uncover patterns that can help **maximize driver revenue** through data-driven insights.

---

## 🎯 Objective

* Analyze how payment methods influence fare distribution
* Identify statistically significant differences in fares
* Derive insights to support driver revenue optimization

---

## 📊 Dataset

The dataset contains ride-level information such as:

* `fare_amount`
* `payment_type` (Card, Cash, Flex)
* `passenger_count`
* Trip-related attributes

---

## Methodology

### 1. Data Cleaning

* Handled missing values
* Standardized `payment_type` values (case normalization)
* Removed invalid fare entries

---

### 2. Exploratory Data Analysis (EDA)

* Analyzed fare distribution across payment types
* Visualized patterns using histograms and stacked bar charts

---

### 3. Data Transformation

* Created pivot tables to analyze passenger distribution
* Converted categorical variables for analysis

---

### 4. Hypothesis Testing (ANOVA)

Performed One-Way ANOVA to evaluate differences in fare:

**Null Hypothesis (H₀):**
Fare amount is the same across all payment types

**Alternative Hypothesis (H₁):**
Fare amount differs across payment types


---

## 📈 Results

* **F-statistic:** 12807.11
* **p-value:** ~0.0

### ✅ Conclusion

* Reject the null hypothesis (p < 0.05)
* There is a **statistically significant difference in fare amounts across payment types**

###  Final insights
1. Customers tend to prefer card payments on longer, higher-value trips, while cash is chosen for shorter and cheaper rides — suggesting that payment behaviour is driven by trip value, not habit.

2. Since card and flex payments are associated with higher-fare trips, encouraging drivers to accept digital payments and nudging cash customers toward card could directly increase per-trip earnings without needing to increase ride volume.


---

## 💡 Key Insights

* Payment type influences fare distribution
* Card payments dominate across most trips
* Flex payments are mostly used for single-passenger rides
* Fare variation suggests multiple underlying pricing factors

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy



## 🧠 Learning Outcomes

* Applied hypothesis testing (ANOVA) on real-world data
* Gained experience in data cleaning and transformation
* Built data visualization and storytelling skills
* Interpreted statistical results for business insights

