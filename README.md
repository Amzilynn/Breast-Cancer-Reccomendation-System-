# Hybrid Content-Based + Knowledge-Based Recommendation System

## Overview

This project implements a hybrid recommendation system that combines
content-based analysis with a knowledge-based rule engine to generate
personalized metabolic recommendations for breast cancer patients.

The system analyzes a patient’s metabolic biomarker profile, compares it
to healthy reference values, assigns a severity context using clustering,
and produces explainable, evidence-based recommendations.


---

## System Objective

- Compare patient metabolic profiles to healthy norms
- Quantify deviations using statistical measures
- Assign severity context using clustering
- Apply medical knowledge through rule-based reasoning
- Generate personalized and explainable recommendations

---
## High-Level Pipeline

Patient Biomarker Profile
        |
        v
Content-Based Analysis
(Z-scores, deviation labels)
        |
        v
Cluster Assignment
(K-Means, severity context)
        |
        v
Knowledge-Based Reasoning
(If–then rules, medical guidelines)
        |
        v
Personalized Recommendations


---

## Theoretical Framework

### Content-Based Component

- Uses statistical comparison against a healthy baseline
- Computes Z-scores for each biomarker
- Assigns deviation labels (low / normal / high)
- Builds a per-patient deviation profile

### Severity Context (Clustering)

- Applies K-Means clustering to cancer patients
- Uses K = 3 to represent different metabolic severity patterns
- Each cluster represents a distinct metabolic phenotype

### Knowledge-Based Component

- Encodes clinical expertise as explicit rules
- Combines cluster membership and biomarker deviations
- Produces explainable and medically grounded recommendations

---

## Dataset

**Coimbra Breast Cancer Dataset**

- Total samples: 116
- Biomarkers: 9 metabolic features
- Class distribution:
  - Class 1: Healthy patients (52)
  - Class 2: Breast cancer patients (64)

---

## Key Features

- Hybrid AI approach (statistical + symbolic)
- Explainable decision-making
- Severity-aware personalization
- Clinically interpretable outputs
- Modular and extensible design

---

## Future Work

- Add additional clinical variables
- Validate rules with medical experts
- Support longitudinal patient monitoring

---

## Disclaimer

This project is intended for research and decision-support purposes only.
It does not replace professional medical diagnosis or clinical judgment.

---

## Author

El Jazi Amal

