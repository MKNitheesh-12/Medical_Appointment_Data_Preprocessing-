# 🏥 Medical Appointment No-Show Analysis
### Data Preprocessing Pipeline

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.5+-yellow.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.24+-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-red.svg)

## 📋 Overview

This project focuses on preprocessing the **Medical Appointment No-Show** dataset, preparing it for predictive modeling and analysis. The goal is to clean, transform, and engineer features to understand and predict patient no-show behavior.

### 📊 Dataset Statistics

| Metric | Value |
|--------|-------|
| **Total Records** | 110,527 |
| **Original Features** | 14 |
| **Final Features** | 28 |
| **No-Show Rate** | 20.19% |
| **Patient Gender Distribution** | F: 65.7% \| M: 34.3% |

---

## 🔄 Data Preprocessing Pipeline

### 1️⃣ Data Loading & Initial Inspection

The dataset was loaded and examined for structure, data types, and completeness.

```python
# Dataset contains 110,527 rows and 14 columns
# No missing values found in any column
# Duplicate records: 0
