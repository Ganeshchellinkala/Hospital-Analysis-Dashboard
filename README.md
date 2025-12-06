# Hospital Data Analysis Dashboard
A comprehensive Excel-based analytical dashboard designed to deliver actionable insights into hospital operations, patient activity, financial workflows, and clinical procedures.

## 1. Project Overview

The Hospital Data Analysis Dashboard is a dynamic and interactive Excel reporting solution built to analyze key hospital functions across patient demographics, encounters, procedures, payers, and organizational performance. This dashboard centralizes operational data to help stakeholders monitor clinical efficiency, patient flow, treatment patterns, and payer trends—enabling informed, data-driven decision-making across the healthcare ecosystem.

 ## 2. Purpose & Objectives
Business Problem

Hospitals generate extensive operational and clinical data, but this information often remains scattered across multiple systems—making it difficult to evaluate performance, optimize resources, or identify improvement opportunities. Administrators, clinicians, and financial teams need a single unified platform to understand:

How many patients are being treated ?

What types of procedures are performed ?

Which payers contribute the most ?

Trends in admissions, discharge, and treatment ?

Organizational workload and patient demographics ?

 ## Goal of the Dashboard 

To deliver an easy-to-use visual analytics tool that:

Tracks patient encounters and treatment patterns

Highlights high-volume procedures and their distribution

Analyzes payer contribution trends

Provides department-wise workload insights

Supports hospital leadership in operational planning

## Who Can Use It?

Hospital Administrators

Healthcare Analysts

Quality & Compliance Teams

Financial / Billing Teams

Clinicians & Department Heads

## 3. Tech Stack / Tools Used

The dashboard was built using the following tools and technologies:

📊 Microsoft Excel (Dashboard Development & Visualizations)

📈 Pivot Tables & Pivot Charts – for aggregated analysis

🔎 Slicers & Filters – for interactivity

📂 Power Query (Optional) – for data cleaning & transformations

📁 Source Data Format – Excel (.xlsx) tables

🧮 Calculated Metrics – LOS (Length of Stay), Encounter Counts, Procedure Rates, etc.

## 4. Data Sources & Table Structure

The dashboard is built on five core tables, each serving a specific function in hospital analytics:

1. Patients Table

Contains demographic information for each patient.
Key Fields:

Patient_ID

Name

Gender

Age

DOB

Contact Details

2. Encounters Table

Captures every patient interaction with the hospital.
Key Fields:

Encounter_ID

Patient_ID (Linked)

Date of Admission

Date of Discharge

Department / Unit

Encounter Type (IP/OP/ER)

Length of Stay

Physician

3. Procedures Table

Stores all clinical and diagnostic procedures performed.
Key Fields:

Procedure_ID

Encounter_ID (Linked)

Procedure Type

Category (Surgical/Diagnostic/Therapeutic)

Performing Department

Date Performed

4. Payers Table

Details the financial payer associated with each patient or encounter.
Key Fields:

Payer_ID

Payer Name (Insurance / Cash / Govt. Scheme)

Encounter_ID (Linked)

Coverage Type

Claim Amount

5. Organisation Table

Maps organizational hierarchy & hospital metadata.
Key Fields:

Org_ID

Department Name

Capacity

Location

Specialty

## Relationships:

Patients ↔ Encounters → Procedures

Encounters → Payers

Organisation → Encounters / Procedures

 ## 5. Dashboard Features & Highlights
 Key Performance Indicators (KPIs)

Total Patients

Total Encounters

Monthly Admissions & Discharges

Average Length of Stay (LOS)

Total Procedures Performed

Payer Contribution Summary

Department-Wise Patient Load

##  Interactive Filters

Department

Encounter Type (IP/OP/ER)

Payer

Procedure Category

Date Range

Gender / Age Group
