# Assumptions, Constraints & Dependencies

## Maji Ndogo Water Services Project

**Project Type:** Data-Driven Decision Support & Business Intelligence  
**Portfolio Focus:** Project Management + Data Analytics + Business Intelligence  
**Delivery Approach:** Structured End-to-End Project Lifecycle  
**Document:** Assumptions, Constraints & Dependencies  
**Phase:** Project Initiation  

---

## 1. Purpose

This document identifies the assumptions, constraints and dependencies that may influence the successful delivery of the Maji Ndogo Water Services Project.

These factors will be monitored throughout the project lifecycle because changes to them may affect:

- Scope
- Schedule
- Data quality
- Analytical accuracy
- Deliverables
- Project resources
- Business Intelligence outputs
- Decision-support conclusions

The document establishes a baseline for managing uncertainty before the project moves into detailed planning and execution.

---

# 2. Assumptions

An assumption is something considered to be true for planning purposes, even though it has not necessarily been fully verified.

---

## A1 — Source Data Availability

It is assumed that the required Maji Ndogo datasets will remain available throughout the analytical phase of the project.

**Potential Impact if False:**

- Analysis may be delayed.
- Some KPIs may not be reproducible.
- Dashboard development may be affected.

**Mitigation:**

- Maintain copies of approved source datasets.
- Document dataset versions.
- Record source files in the project repository.

---

## A2 — Data Contains Sufficient Analytical Information

It is assumed that the available datasets contain sufficient variables to support the planned analysis.

These may include information relating to:

- Water sources
- Water quality
- Population
- Waiting times
- Infrastructure
- Geographic dimensions
- Investment requirements

**Potential Impact if False:**

Some planned KPIs or analyses may not be possible.

**Mitigation:**

Perform a data assessment before finalising the analytical requirements.

---

## A3 — Data Can Be Transformed for Analysis

It is assumed that the available data can be cleaned and transformed into a suitable analytical structure.

Potential transformation activities include:

- Cleaning
- Standardisation
- Joining
- Aggregation
- Categorisation
- Data-type conversion

**Potential Impact if False:**

Additional data preparation or alternative analytical methods may be required.

---

## A4 — Analytical Calculations Can Be Reproduced

It is assumed that major analytical results can be reproduced using documented formulas, SQL queries, Power Query transformations or Power BI measures.

**Potential Impact if False:**

Reduced confidence in analytical results.

**Mitigation:**

Maintain calculation documentation and perform independent validation.

---

## A5 — Power BI Can Support the Required Analysis

It is assumed that Power BI will be suitable for the required:

- Data modelling
- KPI calculations
- Visualisation
- Filtering
- Dashboard interaction
- Executive reporting

**Potential Impact if False:**

Alternative analytical or visualisation approaches may be required.

---

## A6 — Analytical Findings Can Be Validated

It is assumed that key findings can be reconciled against the source data and analytical calculations.

**Potential Impact if False:**

Dashboard and reporting outputs may require further investigation.

**Mitigation:**

Perform data validation, calculation checks and user acceptance testing.

---

## A7 — Project Documentation Can Be Reconstructed Where Necessary

This portfolio case study represents an end-to-end project lifecycle.

Where historical project-management artefacts were not available in the original analytical work, project-management documents may be reconstructed using professional project-management practices.

These reconstructed documents will be clearly treated as portfolio project artefacts rather than historical organisational records.

---

## A8 — Stakeholder Requirements Can Be Represented

It is assumed that reasonable stakeholder requirements can be established from the business problem, available data and intended decision-support outcomes.

Where actual historical stakeholder requirements are unavailable, requirements will be documented as proposed portfolio requirements.

---

## A9 — AI Can Assist Selected Activities

It is assumed that AI tools can assist with selected repetitive or analytical activities, including:

- Documentation
- Data-analysis assistance
- SQL development assistance
- KPI documentation
- Report drafting
- Insight generation
- Process automation design

AI-generated outputs will require human validation.

---

# 3. Constraints

A constraint is a limitation that restricts the project's available options, resources, time, scope or capabilities.

---

## C1 — Available Data Constraint

The project is restricted to the available Maji Ndogo datasets.

New field data will not be collected as part of this portfolio project.

**Impact:**

The analysis may not address information that is not represented in the source data.

---

## C2 — Data Quality Constraint

The accuracy of the analytical outputs is dependent on the quality of the available source data.

Potential issues may include:

- Missing values
- Incorrect values
- Duplicates
- Inconsistent categories
- Incorrect data types
- Outliers

**Impact:**

Poor source-data quality may affect analytical conclusions.

---

## C3 — Historical Project Information Constraint

The available source material primarily supports the data-analysis component of the project.

A complete historical project-management record may not exist.

**Impact:**

Some project-management artefacts must be developed as part of the portfolio case study.

---

## C4 — Portfolio Scope Constraint

The project is designed as a professional portfolio case study.

It is not intended to replicate the full operational complexity, governance structure or budget of a real infrastructure programme.

---

## C5 — No Physical Implementation

The project does not include physical implementation of water infrastructure.

This includes:

- Construction
- Repairs
- Installation
- Infrastructure maintenance
- Field implementation

---

## C6 — No Funding Authority

The project does not have authority to:

- Approve funding
- Allocate budgets
- Authorise expenditure
- Approve infrastructure investment

Investment figures contained within the analysis are treated as analytical source-data values.

---

## C7 — No New Field Research

The project does not include:

- Community surveys
- Physical inspections
- Laboratory testing
- New field measurements
- Interviews

The analysis is based on available data.

---

## C8 — Technology Constraint

The quality and functionality of the final Business Intelligence solution depend partly on the capabilities of the selected technologies.

Primary technologies include:

- Excel
- Power Query
- SQL
- Power BI
- GitHub
- AI tools

---

## C9 — Resource Constraint

This portfolio project is designed to demonstrate an end-to-end delivery capability within a controlled project environment.

Resource assumptions therefore differ from those of a large-scale organisational programme.

---

## C10 — Analytical Interpretation Constraint

Analytical relationships identified within the data should not automatically be interpreted as causal relationships.

The project will distinguish between:

- Observed patterns
- Correlations
- Analytical indicators
- Potential explanations
- Confirmed causal relationships

---

# 4. Dependencies

A dependency is a relationship where one activity, deliverable or outcome relies on another activity or condition.

---

## D1 — Data Availability Dependency

Data analysis depends on access to the required source datasets.

```text
Source Data
     ↓
Data Assessment
     ↓
Data Preparation
     ↓
Analysis
