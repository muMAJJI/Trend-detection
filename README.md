# 📈 Trend detection

Quantitative Researcher | [Mustafa MAJJI](https://www.linkedin.com/in/mustafa-majji-meng-msc-3a59861a2/)

***
## 🚀 Project Overview

This project focuses on market trend detection using quantitative methods based on unsupervised learning and statistical regression.  
The objective is to classify market conditions into three regimes:

- **Downtrend**: prices are decreasing  
- **Range (Sideways Market)**: prices move laterally with no clear direction  
- **Uptrend**: prices are increasing  

Two complementary approaches are implemented and compared.

---

## 🧠 Methodologies

### 1. K-Means Clustering

K-Means clustering is used as an unsupervised learning technique to identify homogeneous market regimes based on price behavior.

- The number of clusters is fixed to three, representing:
  - Downtrend
  - Range
  - Uptrend

---

### 2. Rolling Window Regression

A regression-based approach is used to detect trends through slope estimation.

- A linear regression is applied over a rolling window
- The slope of the regression line serves as a trend indicator
- Trend classification depends on:
  - The rolling window size
  - Predefined slope thresholds used to distinguish:
    - Downtrend
    - Range
    - Uptrend

This method offers higher interpretability but requires careful parameter tuning.

---




## :mailbox_closed: Contact
For any information, feedback or questions, please [contact me][Mustafa-email]




[Mustafa-email]: mailto:majji1999@gmail.com
