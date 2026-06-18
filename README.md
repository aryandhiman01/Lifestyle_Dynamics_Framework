<div align="center">

# 🌙 Lifestyle_Dynamics_Framework

### 📊 Statistical Analysis & Lifestyle Segmentation using K-Means Clustering

<img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-red?style=for-the-badge">
<img src="https://img.shields.io/badge/Seaborn-EDA-purple?style=for-the-badge">
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-yellow?style=for-the-badge&logo=scikitlearn">

<br><br>

<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Machine%20Learning-KMeans%20Clustering-blueviolet?style=for-the-badge">
<img src="https://img.shields.io/badge/Statistics-Correlation%20%7C%20ANOVA%20%7C%20Chi--Square-informational?style=for-the-badge">

</div>

---

# 📖 Project Overview

Sleep plays a critical role in maintaining overall health and well-being. Poor sleep quality, high stress levels, unhealthy BMI, and low physical activity can negatively impact an individual's lifestyle and health outcomes.

This project analyzes the relationship between sleep health and lifestyle factors using:

- 📊 Exploratory Data Analysis (EDA)
- 📈 Statistical Analysis
- 🤖 Machine Learning (K-Means Clustering)
- 🎯 Personalized Lifestyle Recommendations

The objective is to identify hidden lifestyle patterns and provide meaningful recommendations for healthier living.

---

# 🎯 Problem Statement

Understanding how factors such as:

- Sleep Duration
- Quality of Sleep
- Stress Level
- Physical Activity
- BMI Category
- Occupation

affect an individual's lifestyle and overall health.

---

# 💡 Proposed Solution

The project follows a complete Data Science workflow:

```text
Data Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis (EDA)
        ↓
Statistical Analysis
        ↓
K-Means Clustering
        ↓
Lifestyle Segmentation
        ↓
Personalized Recommendations
```

---

# 📂 Dataset Information

### Dataset

Sleep Health and Lifestyle Dataset

### Dataset Size

| Attribute | Value |
|------------|---------|
| Records | 374 |
| Features | 13 |
| Missing Values | Handled |
| Duplicate Records | Checked |

---

# 📋 Features Used

## 😴 Sleep Features

- Sleep Duration
- Quality of Sleep
- Sleep Disorder

## ❤️ Health Features

- BMI Category
- Heart Rate
- Blood Pressure

## 🏃 Lifestyle Features

- Physical Activity Level
- Daily Steps
- Stress Level

## 👤 Personal Features

- Age
- Gender
- Occupation

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

✅ Missing Value Analysis

✅ Missing Value Handling

✅ Duplicate Record Verification

✅ Data Type Validation

✅ Feature Selection

✅ Feature Scaling using StandardScaler

### Selected Features for Clustering

```python
features = [
    "Sleep Duration",
    "Quality of Sleep",
    "Physical Activity Level",
    "Stress Level",
    "Heart Rate",
    "Daily Steps"
]
```

---

# 📊 Exploratory Data Analysis (EDA)

EDA was conducted to identify trends, distributions, and hidden patterns within the dataset.

### Analysis Performed

- Sleep Analysis
- Health Analysis
- Lifestyle Analysis
- Demographic Analysis

### Key Insights

📌 Higher Stress → Lower Sleep Quality

📌 Better Sleep Duration → Lower Stress

📌 Physical Activity improves Sleep Quality

📌 BMI influences Sleep Health

📌 Sleep Disorders are more common among overweight individuals

---

# 📈 Statistical Analysis

## Correlation Analysis

| Variables | Correlation |
|------------|------------|
| Sleep Quality vs Stress Level | -0.899 |
| Sleep Duration vs Stress Level | -0.811 |
| Sleep Duration vs Heart Rate | -0.516 |
| Sleep Quality vs Physical Activity | +0.193 |

### Findings

- Strong negative relationship between Sleep Quality and Stress Level.
- Better sleep is associated with lower stress.
- Physical activity positively influences sleep quality.

---

## ANOVA Test

### Purpose

To determine whether sleep quality differs significantly across occupations.

### Result

✅ Significant Difference Found

### Conclusion

Occupation significantly affects sleep quality.

---

## Chi-Square Test

### Purpose

To determine the association between BMI Category and Sleep Disorder.

### Result

✅ Significant Association Found

### Conclusion

BMI Category is strongly associated with Sleep Disorders.

---

# 🤖 Machine Learning

## K-Means Clustering

K-Means Clustering was used to identify hidden lifestyle patterns.

### Features Used

- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- Heart Rate
- Daily Steps

### Optimal Clusters

The Elbow Method identified:

```text
Optimal Number of Clusters = 3
```

---

# 🎯 Lifestyle Segmentation

## 🟢 Optimal Lifestyle

**239 Individuals (63.9%)**

- Good Sleep Quality
- Low Stress
- Healthy Activity Level

---

## 🟡 Active but Stressed

**34 Individuals (9.1%)**

- High Physical Activity
- High Daily Steps
- High Stress Levels

---

## 🔴 High Risk Lifestyle

**101 Individuals (27.0%)**

- Poor Sleep Quality
- Low Activity Level
- High Stress

---

# 💡 Personalized Recommendations

## 🟢 Optimal Lifestyle

- Maintain sleep habits
- Continue exercise
- Maintain low stress levels

---

## 🟡 Active but Stressed

- Reduce stress
- Practice meditation
- Improve recovery

---

## 🔴 High Risk Lifestyle

- Increase physical activity
- Improve sleep quality
- Reduce stress levels

---

# 📊 Key Project Findings

✅ Sleep Quality and Stress Level showed the strongest relationship (-0.899)

✅ Sleep Duration is negatively associated with Stress Level (-0.811)

✅ Occupation significantly affects Sleep Quality

✅ BMI Category is associated with Sleep Disorders

✅ Three meaningful lifestyle groups were identified using K-Means Clustering

---

# 🚀 Future Scope

- Real-Time Health Monitoring
- Wearable Device Integration
- AI-Based Health Recommendations
- Sleep Disorder Prediction System
- Personalized Health Dashboard

---

# 🏆 Conclusion

This project successfully analyzed the impact of sleep, stress, physical activity, BMI, and occupation on lifestyle health.

Using Statistical Analysis and K-Means Clustering, individuals were segmented into meaningful lifestyle groups and provided with personalized recommendations to improve overall well-being.

---

<div align="center">

# 🌟 Final Takeaway

### Better Sleep + Lower Stress + Regular Physical Activity

### =

### Healthier Lifestyle & Improved Well-Being

<br>

### ⭐ If you found this project useful, give it a star!

</div>
