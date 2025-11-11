# AHRI Health Informatics Internship Assessment

**Author:** Simon Mufara  
**Date:** November 2025  
**Project:** Health Screening & Clinic Attendance Analysis – AHRI, KwaZulu-Natal  

---

## Project Overview

This repository contains the complete analysis for the AHRI Health Informatics Internship Assessment. The objective of this assessment is to investigate clinic attendance patterns among participants diagnosed with hypertension during a health screening in rural KwaZulu-Natal (2018–2019).  

The key goals were:  
1. Identify errors or inconsistencies in the datasets.  
2. Visualize participant demographics, clinic visits, and reasons for visits.  
3. Analyze patterns of clinic attendance among hypertensive participants and the broader participant group.  

---

## Datasets

The analysis uses the following datasets provided by AHRI:  

| File | Description |
|------|-------------|
| `participants.csv` | Participant IDs, sex, and date of birth |
| `health_screen.csv` | Blood pressure readings, BMI, smoking status, hypertension diagnosis |
| `clinic_visits.csv` | Participant clinic visit dates and reasons |
| `clinic_codes.csv` | Clinic ID codes for all visits |

> **Note:** All datasets are stored in the root directory of this repo.

---

## Data Cleaning & Quality Checks

The following preprocessing steps were applied:  
- Standardized column names to lowercase and stripped whitespace.  
- Converted date columns (`dateofbirth`, `date_screen`, `visitdate`) to datetime format.  
- Standardized text fields (`bpdiag`, `smokecat`, `sex`, `visitreason`) to lowercase.  
- Checked for missing values and duplicate rows.  
- Merged datasets for analysis using `id_new` as the key.  

---

## Analysis & Findings

1. **Hypertensive Participants**  
   - Total hypertensive participants: `X`  
   - Hypertensive participants who attended a clinic: `Y`  

2. **Clinic Visits for Hypertension**  
   - Participants who visited the clinic for hypertension-related reasons: `Z`  

3. **Other Participants**  
   - Non-hypertensive participants who attended a clinic: `W`  

4. **Most Common Reasons for Visits**  
   - Top reasons:  
     - Reason 1: `Count`  
     - Reason 2: `Count`  
     - …  

---

## Visualizations

The following visualizations were generated and saved in the `figures/` directory:

1. **Age Distribution of Participants** – histogram with KDE.  
2. **Top 10 Reasons for Clinic Visits** – horizontal bar chart.  
3. **Clinic Attendance Among Hypertensive Participants** – pie chart.  
4. **Optional Advanced Visualizations** – interactive plots using Plotly for enhanced presentation.


