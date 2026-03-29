# Application-of-Inferential-Statistics

## 🚀 Project Overview
This project demonstrates the application of **Inferential Statistics** techniques to solve real-world analytical problems across multiple domains including **sports analytics, manufacturing quality, material science, and healthcare**.

The analysis focuses on:
- Probability & distributions  
- Hypothesis testing  
- T-tests & ANOVA  
- Statistical decision-making  

---

## 🎯 Objectives
- Apply statistical methods to real datasets  
- Interpret results for business/scientific decisions  
- Identify patterns, relationships, and variability  


---

## ⚽ Problem 1: Player Injury Analysis

### 📌 Goal
Analyze the relationship between **player position** and **injury occurrence**.

### 📊 Dataset Summary

| Position    | Injured | Not Injured | Total |
|------------|--------|------------|-------|
| Striker    | 45     | 32         | 77    |
| Forward    | 56     | 38         | 94    |
| Midfielder | 24     | 11         | 35    |
| Winger     | 20     | 9          | 29    |
| **Total**  | 145    | 90         | 235   |

### 📊 Key Insights
- Probability of injury: **0.6170**  
- Probability of forward or winger: **0.5234**  
- Probability of striker & injured: **0.1915**  
- Probability that injured player is a striker: **0.3103**  

### 📈 Interpretation
Offensive roles show higher injury exposure, indicating increased physical risk.

---

## 📦 Problem 2: Quality Control (Normal Distribution)

### 📌 Goal
Evaluate **breaking strength of gunny bags** using normal distribution.

- Mean (μ) = 5 kg/cm²  
- Standard Deviation (σ) = 1.5 kg/cm²  

### 📊 Key Results
- P(X < 3.17) = **0.1112**  
- P(X ≥ 3.6) = **0.8247**  
- P(5 ≤ X ≤ 5.5) = **0.1306**  
- P(X not between 3 and 7.5) = **0.139**  

### 📈 Interpretation
Majority of products meet quality standards, but defective minority exists.

---

## 🧩 Problem 3: Hypothesis Testing (T-Test)

### 📌 3.1 Suitability of Unpolished Stones
- Test: One-sample T-test  
- H₀: μ = 150  
- H₁: μ < 150  
- p-value = **4.17e-05**

✅ **Conclusion:** Reject H₀ → Unpolished stones are not suitable  

---

### 📌 3.2 Polished vs Unpolished Comparison
- Test: Two-sample T-test  
- p-value = **0.9992**

✅ **Conclusion:** Fail to reject H₀ → Means are equal  

---

## 🦷 Problem 4: Dental Implant Analysis (ANOVA)

### 📌 Goal
Analyze hardness variation based on:
- Dentist  
- Method  
- Alloy  

---

### 🔬 4.1 Effect of Dentist
- No significant difference  
- Mean hardness is similar  

---

### 🔬 4.2 Effect of Method
- Significant differences exist  
- Mean hardness varies across methods  

---

### 🔬 4.3 Interaction Effect
- Interaction exists between Dentist & Method  

---

### 🔬 4.4 Two-Way ANOVA

#### Alloy 1:
- p-value < 0.05  
✅ Significant interaction  

#### Alloy 2:
- p-value > 0.05  
❌ No significant interaction  

---

## 🧠 Key Learnings
- Applied **probability models** to real scenarios  
- Understood **statistical significance**  
- Performed:
  - T-tests  
  - ANOVA  
  - Distribution analysis  
- Identified **interaction effects in multi-variable systems**  

---

## 🛠️ Tech Stack & Methods
- Python (Statistical Analysis)
- Hypothesis Testing
- ANOVA / Two-Way ANOVA
- Probability Distributions

---
