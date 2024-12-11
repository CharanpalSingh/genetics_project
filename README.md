# Genetics Project

## Overview
This project involves analyzing clinical and genetic datasets and performing specific statistical analyses. The work demonstrates data manipulation, statistical modeling, and result interpretation skills.

---

## Datasets

The project utilizes two datasets:

1. **Clinical Data (clinical_data.xlsx):**
   - Includes standardized scores (tscores) adjusted for age, respondent type (self/parent), and in some cases, gender.
   - Contains a data dictionary explaining the variables.

2. **Genetic Data (genetic_data.txt):**
   - Summarizes polygenic risk scores (PRS) for various mental health traits:
     - ADHD (Attention Deficit/Hyperactivity Disorder)
     - ASD (Autism Spectrum Disorder)
     - Aggression
     - Executive Function
     - Irritability
     - MDD (Major Depressive Disorder)
     - OCD (Obsessive/Compulsive Disorder)
   - The PRS variables are approximately normally distributed.

---

## Tasks and Objectives

### 1. **Data Exploration and Summary:**
   - Examine both datasets for key anomalies (e.g., outliers, unusual distributions).
   - Summarize observations in a brief report.

### 2. **Statistical Analyses:**

#### A. Linear Regression
   - Response Variable: `tocs_mf_tscores`
   - Explanatory Variables: `sex`, `OCD.prs`

#### B. Logistic Regression
   - Response Variable: `dx_adhd`
   - Explanatory Variables: `sex`, `ADHD.prs`

   - Interpret the regression coefficients and associated statistics without requiring domain knowledge of the variables.

---

## Project Structure

- **Data Files:**
  - `clinical_data.xlsx`: Contains clinical information and a data dictionary.
  - `genetic_data.txt`: Contains polygenic risk scores.

- **Scripts:**
  - `data_analysis.R`: Script used to analyze the data and perform statistical modeling.

- **Results:**
  - `powerpoint_final`: A concise report summarizing data insights and anomalies.

- **README.md:** Project documentation (this file).

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-analysis-project.git
