# AHRI Health Informatics Internship Assessment

**Author:** Simon Mufara
**Date:** November 2025
**Institution:** Africa Health Research Institute (AHRI), KwaZulu-Natal

---

## Overview

This repository contains my analysis for the **AHRI Health Informatics Internship Assessment**, focused on understanding **clinic attendance patterns among hypertensive participants** from rural KwaZulu-Natal (2018–2019).

The project integrates data from multiple AHRI datasets to answer key questions about **hypertension diagnosis, clinic attendance, and visit reasons**.

---

## Datasets

| File                | Description                                    |
| ------------------- | ---------------------------------------------- |
| `participants.csv`  | Participant demographics                       |
| `health_screen.csv` | Health screening data including blood pressure |
| `clinic_visits.csv` | Clinic visit details and reasons               |
| `clinic_codes.csv`  | Clinic ID reference table                      |

---

## Project Files

| File                                       | Purpose                           |
| ------------------------------------------ | --------------------------------- |
| `Simon_Mufara_AHRI_Assessment_Final.ipynb` | Main analysis and visualizations  |
| `merged_ahri_data.xlsx`                    | Cleaned and merged dataset        |
| `output_ahri_q1/`                          | Final figures and QC reports      |
| `How_to_run_the_project.md`                | Instructions to reproduce results |

---

## Quick Start

```bash
pip install -r requirements.txt
jupyter notebook Simon_Mufara_AHRI_Assessment_Final.ipynb
```

Outputs are saved automatically in `output_ahri_q1/` and `output_ahri_visuals_final/`.

---

## Key Focus

* Identify hypertensive participants who attended clinics
* Determine frequency of hypertension-related visits
* Compare attendance with non-hypertensive participants
* Explore the most common reasons for visits

---

## Visual Outputs

All visualizations are available in the `figures/` directory, including:

* Age distribution
* Clinic attendance breakdown
* Top 10 visit reasons
* Interactive Plotly visualizations

---

## Note

All data used here are anonymized and for educational use only.


