# TCGA Breast Cancer Clinical Analysis

A medical data analysis project exploring survival patterns in breast cancer patients using the TCGA-BRCA clinical dataset.

## Project Overview

This project analyses clinical data from 990 breast cancer patients from The Cancer Genome Atlas (TCGA) Breast Cancer (BRCA) dataset. The analysis explores relationships between cancer stage, patient age, treatment type, and survival outcomes.

## Dataset

- **Source:** The Cancer Genome Atlas (TCGA) — GDC Data Portal
- **Dataset:** TCGA-BRCA Clinical Data
- **Patients analysed:** 990 breast cancer patients
- **Variables used:** Age, vital status, cancer stage, survival days, treatment type

## Key Findings

### 1. Patient Overview
- 89% of patients are alive at last follow up
- Average patient age at diagnosis: 58.5 years
- Average survival time: 1189 days (~3.3 years)

### 2. Cancer Stage and Survival
- Stage I patients survived ~1786 days on average (~4.9 years)
- Stage IIIC patients survived ~793 days on average (~2.2 years)
- Clear trend: earlier stage = significantly longer survival

### 3. Age and Survival
- Patients under 40 survived ~1439 days on average
- Patients over 70 survived ~932 days on average
- Younger patients consistently survive longer across all age groups

### 4. Treatment and Survival
- Immunotherapy showed highest average survival: ~2043 days
- Surgery was the most common treatment
- Standard treatments show similar survival rates (~1200 days)

## Visualisations

1. Age distribution of breast cancer patients
2. Vital status — alive vs dead
3. Distribution of cancer stages
4. Survival days by cancer stage
5. Most common treatment types

## Tools and Libraries

- Python 3
- Pandas — data loading and cleaning
- NumPy — numerical calculations
- Matplotlib — data visualisation
- Seaborn — statistical visualisation

## How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `notebooks/analysis.ipynb` in Jupyter Notebook
4. Run all cells in order

## Author

Ravindu Denuwan | 2026
