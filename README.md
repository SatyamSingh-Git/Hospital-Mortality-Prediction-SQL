<div align="center">

# 🏥 Hospital Mortality Prediction

### *Data-Driven Insights to Improve Patient Outcomes*

[![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://www.tableau.com/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/excel)

[📊 View Dashboard](https://public.tableau.com/app/profile/sharif.athar/viz/HospitalMortalityDashboard/Dashboard1) • [💾 Dataset](https://www.kaggle.com/datasets/mitishaagarwal/patient) • [📝 SQL Code](https://github.com/SharifAthar/Hospital-Mortality-Prediction-SQL/blob/main/Hospital_Mortality_SQL_Analysis.sql)

<img src="https://media.istockphoto.com/id/1194838627/vector/patient-in-hospital.jpg?s=612x612&w=0&k=20&c=LqhY8qXr1IgGA0PjGLwqEyVJL-MBTFBU5rf3Dcg4DWo=" alt="Hospital Patient" width="600"/>

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Business Problem](#-business-problem)
- [Methodology](#-methodology)
- [Key Findings](#-key-findings)
- [Data Analysis](#-data-analysis)
- [Conclusions](#-conclusions)
- [Recommendations](#-recommendations)
- [Tech Stack](#-tech-stack)

---

## 🎯 Overview

This project analyzes hospital patient data to identify key factors contributing to in-hospital mortality. By leveraging SQL analytics and interactive visualizations, we uncover patterns that can help healthcare professionals improve patient care and reduce mortality rates.

**Dataset**: 10,000 patient records with comprehensive medical and demographic information

---

## 💼 Business Problem

Healthcare professionals need to identify the main causes of in-hospital mortality for admitted patients. Early identification of risk factors enables:

- 🎯 Proactive intervention strategies
- 📊 Better resource allocation
- 💡 Improved patient care protocols
- 📈 Reduced mortality rates

---

## 🔍 Methodology

### Analytical Approach

1. **Data Exploration**: Comprehensive analysis of patient demographics, medical conditions, and outcomes
2. **SQL Analytics**: Complex queries to identify patterns and correlations
3. **Statistical Analysis**: Mortality rate calculations across multiple dimensions
4. **Visualization**: Interactive Tableau dashboard for stakeholder insights

### Key Metrics Analyzed

- Age distribution and mortality correlation
- ICU admission sources and types
- Comorbidity impact on survival rates
- Length of stay vs. mortality
- Vital signs and physical characteristics

---

## 🔑 Key Findings

### 📊 Overall Mortality Rate

![Query1](https://i.ibb.co/SV4r1Rt/Screen-Shot-2023-06-29-at-4-52-19-PM.png)

**634 deaths out of 10,000 patients (6.34% mortality rate)** - highlighting the critical need for identifying contributing factors.

---

### 👥 Age-Based Analysis

![Query2](https://i.ibb.co/XC5qXg8/Screen-Shot-2023-06-29-at-7-44-37-PM.png)

**Finding**: Significantly higher patient admissions in the 50-89 age range, with mortality increasing with age.

![Query3](https://i.ibb.co/MnB3M5L/Screen-Shot-2023-06-29-at-7-56-52-PM.png)

**Key Insight**: Death probability rises proportionally with patient age.

---

### 🏥 ICU Analysis

![Q4](https://i.ibb.co/54ZBMBH/Screen-Shot-2023-06-29-at-8-08-53-PM.png)

![Q5](https://i.ibb.co/mJB1cxY/Screen-Shot-2023-06-29-at-8-09-28-PM.png)

**Findings**:
- Majority of patients admitted through "Accident & Emergency"
- **Med-Surg ICU** shows notably higher mortality rates (outlier)

---

### ⚕️ Patient Vitals

![Q6](https://i.ibb.co/5cCNgyW/Screen-Shot-2023-06-29-at-8-32-29-PM.png)

**Average Metrics for Deceased Patients**:
- Weight: 67.57 kg (149 lbs) - moderate weight
- BMI: 23.3 - normal range
- Heart Rate: Within acceptable parameters

**Insight**: Standard vital signs don't necessarily predict mortality, suggesting other factors play crucial roles.

---

### 🩺 Comorbidity Impact

![Q7](https://i.ibb.co/GHb3dnT/Screen-Shot-2023-06-29-at-8-48-21-PM.png)

**Top 3 High-Risk Comorbidities**:
1. 💉 **Diabetes** - highest mortality correlation
2. 🦠 **Immunosuppression** - significant risk factor
3. 🎗️ **Solid Tumor** - elevated mortality rates

---

### ⏱️ Length of Stay

![Q8](https://i.ibb.co/Tkc9RVr/Screen-Shot-2023-07-01-at-2-56-23-PM.png)

**Finding**: Prolonged ICU stays strongly correlate with higher mortality rates ([research source](https://pubmed.ncbi.nlm.nih.gov/26571190/)).

---

## 📈 Data Analysis

The analysis involved comprehensive SQL queries examining:

| Category | Metrics Analyzed |
|----------|------------------|
| **Demographics** | Age groups, gender distribution |
| **Clinical** | Comorbidities, vital signs, BMI |
| **Operational** | ICU types, admission sources, length of stay |
| **Outcomes** | Mortality rates, survival analysis |

---

## 🎓 Conclusions

### Primary Mortality Predictors

1. **🎂 Age**: Advanced age is the strongest predictor
   - Correlation with multiple medical conditions
   - Decreased recovery capacity
   - Higher complication rates

2. **🏥 ICU Type**: Med-Surg ICU shows elevated mortality
   - Requires further investigation into unit-specific factors

3. **🩺 Comorbidities**: Diabetes, immunosuppression, and solid tumors significantly increase risk

4. **⏱️ ICU Duration**: Extended stays indicate higher mortality probability

---

## 💡 Recommendations

### Immediate Actions

- ⚡ **Enhanced Monitoring**: Implement intensive monitoring for high-risk patient groups (elderly, diabetic, immunosuppressed)
- 🎯 **Resource Allocation**: Prioritize resources for Med-Surg ICU to address elevated mortality
- 📋 **Risk Stratification**: Develop early warning systems based on identified predictors

### Future Enhancements

To improve predictive accuracy, future analysis should include:

- 🧬 Specific medical conditions and diagnoses
- 💊 Medication types and dosages
- 🔬 Laboratory test results and biomarkers
- 👨‍⚕️ Surgical procedures and interventions
- 🏥 Hospital capacity and staffing levels
- 🕐 Timing of interventions

### Data-Driven Improvements

- 📊 Real-time dashboard integration for clinical decision support
- 🤖 Machine learning models for predictive analytics
- 📈 Continuous monitoring and model refinement

---

## 🛠️ Tech Stack

<div align="center">

| Tool | Purpose |
|------|---------|
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | Data analysis and complex querying |
| ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) | Interactive visualization and dashboards |
| ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data preprocessing and initial exploration |

</div>

---

## 📬 Contact

<div align="center">

**Have questions or suggestions?**

Feel free to reach out or open an issue!

[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github)](https://github.com/SatyamSingh-Git)

---

### ⭐ If you found this project helpful, please consider giving it a star!

</div>