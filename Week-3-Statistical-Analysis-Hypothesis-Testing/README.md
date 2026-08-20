# Week 3: Statistical Analysis and Hypothesis Testing in Python

## 📌 Project Overview

This project is part of my **Virtual Data Science with Python Apprentice Internship**.

The objective of Week 3 is to perform statistical analysis and hypothesis testing using Python. The project uses the Medical Insurance Cost dataset to investigate relationships between demographic and lifestyle factors and medical insurance charges.

The analysis includes hypothesis formulation, statistical testing, visualizations, confidence intervals, and interpretation of results.

---

## 📊 Dataset

The dataset used for this project is the **Medical Insurance Cost Dataset**.

It contains the following features:

- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region
- Medical Insurance Charges

---

## 🎯 Research Questions

The project investigates the following questions:

1. Do smokers and non-smokers have significantly different average medical insurance charges?
2. Do average medical insurance charges differ across geographical regions?
3. Is there a significant association between gender and smoking status?

---

## 🧪 Statistical Tests Performed

### 1. Independent Samples t-test

The t-test was used to compare the average medical insurance charges of smokers and non-smokers.

**Null Hypothesis (H₀):**  
There is no significant difference in average insurance charges between smokers and non-smokers.

**Alternative Hypothesis (H₁):**  
There is a significant difference in average insurance charges between smokers and non-smokers.

---

### 2. One-Way ANOVA

ANOVA was used to compare average insurance charges across different geographical regions.

**Null Hypothesis (H₀):**  
There is no significant difference in average insurance charges among the regions.

**Alternative Hypothesis (H₁):**  
At least one region has a significantly different average insurance charge.

---

### 3. Chi-Square Test

The chi-square test was used to examine the relationship between gender and smoking status.

**Null Hypothesis (H₀):**  
There is no significant association between gender and smoking status.

**Alternative Hypothesis (H₁):**  
There is a significant association between gender and smoking status.

---

## 📈 Visualizations

The following visualizations were created:

1. Medical Insurance Charges by Smoking Status
2. Distribution of Insurance Charges by Smoking Status
3. Average Insurance Charges by Region
4. Smoking Status by Gender
5. Distribution of Medical Insurance Charges

---

## 📊 Additional Statistical Analysis

A **95% confidence interval** was calculated for the mean medical insurance charges to estimate the likely range of the population mean.

The significance level used for hypothesis testing was:

```text
α = 0.05
