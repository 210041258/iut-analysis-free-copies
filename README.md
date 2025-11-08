# 📊 Student Performance Analysis

**Training Models • Performance Measurements • Growth Tracking**

---

## 📌 Overview

This project analyzes student academic performance across multiple assessments using **statistical and machine-learning techniques**.  
The goal is to measure:

- 🧠 **Knowledge Improvement:** Course 1 ➝ Course 2  
- 📈 **Midterm Performance Distributions**  
- 🎯 **Growth Delta** with respect to (y+z) components  
- 🔍 **Score Comparisons** across students  

The repository also includes **visualizations** and **processed datasets** for further modeling and evaluation.

---

## 📂 Repository Structure

| Folder / File | Description |
|---------------|-------------|
| `MidTerm_Marks_Distribution/` | Histograms, boxplots & density plots for mid-term scores |
| `Performance_Comparison/` | Student performance comparison between two courses |
| `Growth_Delta/` | Marks growth analysis with respect to (y+z) |
| `final-distribution.png` | Final version of mid-term distribution visualization |
| `final-mid-mark.png` | Cleaned mid-term marks plot |
| `final-quizes.png` | Quizzes vs performance visual output |
| `finalandmid.png` | Combined final + midterm marks correlation figure |
| `theory-percentage.png` | Theory marks distribution figure |
| `README.md` | Documentation (this file) |

---

## 📈 Key Visual Insights

✅ Understanding students’ performance trends  
✅ Identifying weak and strong scoring areas  
✅ Measuring academic growth between courses  
✅ Evaluating consistency between midterm and final performance  

---

## 🧪 Techniques & Methods

- **Data Cleaning & Processing**  
- **Exploratory Data Analysis (EDA)**  
- **Growth Rate & Delta Evaluation**  
- **Statistical Visualization:** Histogram, Boxplot, KDE, Scatter  

**Tools:** Python • Pandas • Matplotlib • Seaborn • Jupyter Notebooks  

---

## 🧩 Planned Enhancements

- ✅ Add CSV dataset for public training and testing  
- 🚧 Include machine learning models for grade prediction  
- 📊 Add interactive dashboards (Plotly / Streamlit)  

---

## 🤝 Contributions

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to update.

---

## 📝 Detailed Analysis Summary

**Student Performance Analysis Across Three Courses**  

This document summarizes the findings from a multi-course data analysis involving student marks from:  

- Mid-Term (Course 1)  
- Course Total (Course 2)  
- OS Lab Evaluation (Course 3)  

The goal was to determine predictive relationships and identify students demonstrating high adaptability ("Growth").

### 1. Predictive Relationship: Course 1 → Course 2

- **Strength of Prediction ($R^2$):** **0.806** (Very strong fit)  
- **Interpretation:** Over 80% of variation in Course 2 results is explained by Course 1 Mid-Term score.  

**Predictive Model (Equation 1):**

$$
\text{Course2\_Total} = (2.29 \times \text{Course1\_Mark}) + 1.25
$$

- Used to calculate **Growth (Delta) C2**, highlighting students who significantly improved or underperformed.

### 2. Predictive Relationship: Courses 1 & 2 → Course 3

- **Strength of Prediction ($R^2$):** **0.195** (Weak fit)  
- **Interpretation:** Performance in Courses 1 and 2 explains <20% of variation in Course 3, indicating different skill requirements.  

**Predictive Model (Equation 2):**

$$
\text{Course3\_Mark} = (0.02 \times \text{Course1\_Mark}) + (0.10 \times \text{Course2\_Total}) + 37.60
$$

- Used to calculate **Growth (Delta) C3**, identifying students best adapted to the new subject.

### 3. Key Student Insights (Growth & Adaptability)

| Student Name | Delta C2 (Growth) | Delta C3 (Adaptability) |
|--------------|-----------------|------------------------|
| Umme Hunny Khan | +79.5 | +4.09 |
| Sameen Yeaser Adib | -14.6 | +13.03 |
| J. M Areeb Uzair Alam | +4.9 | -11.67 |

**Conclusion:** Skill Divergence  

- **Track A (C1 & C2):** Sequential, foundational knowledge.  
- **Track B (C3):** Specialized, independent skills.  

Targeted academic support can be provided for students like **Sameen Yeaser Adib** (high C3 adaptability) and **J. M Areeb Uzair Alam** (low C3 adaptability despite strong C1/C2 scores).

---

## 🔖 Tags

`training · machine-learning · models · performance · student-analysis · discoverabletopic`
