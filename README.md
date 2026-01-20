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
