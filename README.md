# British Airways Data Science Virtual Experience

This repository contains my completed project deliverables for the **British Airways Data Science Job Simulation** hosted on Forage. The program involved acting as a Data Scientist to solve two critical operational and marketing challenges for the airline using analytics and machine learning.

---

## 📋 Project Overview

### ✈️ Task 1: Premium Lounge Eligibility & Demand Forecasting
*   **Business Objective:** Support the Heathrow Terminal 3 Airport Planning team by building a scalable baseline forecast model to predict crowd sizes at premium lounges (Tiers 1, 2, and 3) using standard flight schedules.
*   **Technical Approach:** Standardized varying flight departure schedules into specific time windows (Morning, Lunchtime, Afternoon, Evening) and developed a multi-key Pandas merge/lookup matrix to dynamically scale fleet seat capacities against tier eligibility ratios. 
*   **Key Insight:** Identified critical operational bottleneck surges during evening long-haul flight blocks, allowing airport management to optimize staffing and lounge supply chain workflows.

### 🤖 Task 2: Predictive Customer Acquisition Modeling
*   **Business Objective:** Analyze historical customer behavioral indicators to build a binary classification pipeline predicting which travelers are highly likely to purchase an extra holiday itinerary.
*   **Technical Approach:** Cleaned and encoded booking behavioral data (e.g., stay duration, lead time, routing profile), built a **Random Forest Classifier**, and evaluated performance using Precision, Recall, and AUC-ROC curves.
*   **Business Deliverable:** Compiled technical discoveries into an executive board presentation mapping out algorithmic feature importance metrics to guide target marketing campaigns.

---

## 🛠️ Tech Stack & Tools
*   **Environment:** Google Colab / Jupyter Notebooks
*   **Language:** Python 3.x
*   **Data Manipulation:** Pandas, NumPy
*   **Machine Learning:** Scikit-Learn
*   **Visualization:** Matplotlib, Seaborn

---

## 📁 Repository Structure
```text
├── Data/
│   ├── flight_schedule.csv               # Raw Task 1 flight log schema
│   └── customer_booking_activity.csv     # Raw Task 2 predictive baseline logs
├── Scripts/
│   ├── lounge_demand_forecast.py          # Task 1 allocation merge lookups
│   └── booking_prediction_pipeline.py     # Task 2 Random Forest implementation
├── Deliverables/
│   ├── BA_Lounge_Demand_Forecast_Final.csv # Task 1 processed metrics file
│   └── Executive_Board_Presentation.pdf   # Task 2 executive slide deliverable
└── README.md
```

---

## 📊 Sample Execution: Lounge Forecast Engine

To reproduce the Task 1 data merge lookup engine locally, navigate to the `Scripts/` directory and run:

```bash
python lounge_demand_forecast.py
```

### Generated Capacity Baseline Output:
```text
=== HEATHROW TERMINAL 3 AGGREGATE LOUNGE DEMAND FORECAST ===
             Predicted_Tier_1  Predicted_Tier_2  Predicted_Tier_3
TIME_OF_DAY                                                      
Morning                1450.0            5640.0            4820.0
Lunchtime               890.0            3410.0            2950.0
Afternoon              2100.0            8120.0            7050.0
Evening                4350.0           16780.0           14220.0
```

---

## 🎓 Verifiable Certification
*   **Credential Status:** Completed & Verified
*   **Platform:** Forage Virtual Experience Program
*   **Acquired Competencies:** Data Engineering pipelines, database lookups via vector structures, statistical performance auditing, and corporate executive presentation alignment.

---
*Disclaimer: This project was completed as part of a virtual job simulation loop mapping out realistic corporate case workflows provided by British Airways via Forage.*
