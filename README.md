# Smoking Health Risk Analysis

## Project Overview

The **Smoking Health Risk Analysis** dashboard is an interactive Power BI project designed to explore patterns between smoking behaviour and selected health-related indicators.

The dashboard provides a patient-level view of smoking status, smoking duration, daily cigarette consumption, age groups, cholesterol levels, blood-pressure risk, BMI, and gender.

It also includes interactive filters for **health condition** and **organ condition**, allowing users to explore the dashboard from different health perspectives.

---

## Dashboard Preview

![Smoking Health Risk Analysis](Screenshots/Smoking_Health_Risk_Analysis.png)

---

## Key Dashboard Metrics

The dashboard provides an overview of:

- Total patients
- Average patient age
- Average BMI
- Smoking-status distribution
- Smoking duration
- Daily cigarette consumption
- Cholesterol levels
- Blood-pressure risk
- Gender distribution across smoking categories

---

## Key Visualizations

### 1. Patient Overview

The dashboard begins with high-level patient metrics:

- Total Patients
- Average Age
- Average BMI

These metrics provide a quick summary of the selected patient population.

### 2. Smoking Status Distribution

A donut chart shows the distribution of patients across:

- Never smokers
- Current smokers
- Former smokers

This provides a quick view of the composition of the patient population by smoking status.

### 3. Smoking Exposure by Patient

A scatter chart compares:

- Cigarettes consumed per day
- Years of smoking

This visualization helps explore the relationship between daily cigarette intake and smoking duration at the patient level.

### 4. Smoking Duration and Daily Intake

A line chart compares average:

- Years of smoking
- Cigarettes consumed per day

across different age groups.

This allows users to examine how smoking exposure varies across age segments.

### 5. Smoking Status by Gender

A ribbon chart compares smoking-status categories across:

- Female
- Male

The visualization provides a comparison of gender distribution among current, former, and never smokers.

### 6. Cholesterol and Hypertension Risk

A column chart analyzes patient distribution across age groups and blood-pressure risk levels, with cholesterol level included as the quantitative measure.

This provides a way to explore how these health indicators are distributed across different age groups.

---

## Interactive Features

The dashboard includes interactive filtering capabilities.

### Health Condition Filter

Users can switch between health-condition categories such as:

- Healthy
- Damaged

### Organ Filter

Users can select different organs from the interactive organ navigation, including:

- Heart
- Human Body
- Kidney
- Liver
- Lungs

The selected filters dynamically affect the dashboard visuals.

---

## Data Analysis

The analysis focuses on the following dimensions:

| Category | Fields / Metrics |
|---|---|
| Patient | Patient ID |
| Demographics | Age, Age Group, Gender |
| Smoking | Smoking Status, Years of Smoking, Cigarettes per Day |
| Health | BMI, Cholesterol Level, BP Risk |
| Condition | Organ Condition |
| Organ | Organ |

The dashboard is designed primarily for **descriptive analysis** and exploration of patterns within the dataset. It does not establish medical causation or provide clinical diagnoses.

---

## Power BI Implementation

### Data Modeling

The report uses a primary health dataset along with supporting tables for:

- Organ conditions
- Organ navigation
- Organ icons/images

### DAX

DAX measures are used to calculate and display summary metrics such as:

- Patient count
- Average age
- Average BMI

### Interactive Reporting

Power BI interactions are used to allow selections from the health-condition and organ filters to update the report dynamically.

---

## Tools & Technologies

- **Power BI**
- **DAX**
- **Power Query**
- **Data Modeling**
- **Data Visualization**
- **Business / Healthcare Analytics**

---

## Business Questions Addressed

This dashboard can be used to explore questions such as:

1. How many patients are included in the selected population?
2. What is the distribution of smoking status?
3. How does cigarette consumption vary with years of smoking?
4. How do smoking patterns vary across age groups?
5. How is smoking status distributed across genders?
6. How do cholesterol levels and blood-pressure risk vary across age groups?
7. How do the dashboard metrics change when different health conditions or organs are selected?

---

## Project Structure

```text
Smoking-Health-Risk-Analysis/
│
├── README.md
│
├── Dashboard/
│   └── Smoking_Health_Risk_Analysis.pbix
│
├── Screenshots/
│   └── Smoking_Health_Risk_Analysis.png
│
└── Data/
    └── smoking_health_data.csv
