# Fitbit Fitness Tracker Analysis

An end-to-end data processing and exploratory analysis pipeline evaluating longitudinal behavioral telemetry from personal Fitbit devices. This project investigates physical exertion, energy expenditure, sleep patterns, and daily device adherence across a multi-week monitoring period.

---

## Data Source

* **Dataset:** [FitBit Fitness Tracker Data (Möbius)](https://www.kaggle.com/datasets/arashnic/fitbit)
* **Original Study:** Generated from an open-source health survey by Furberg et al., distributed via Zenodo.
* **Scope:** 30+ consenting adult users tracked between March and May 2016, with data split across daily aggregates, hourly telemetry, and minute-level logs.

---

## Repository Structure

```text
├── notebooks/
│   ├── data_cleaning.ipynb       # Ingestion, validation, and feature engineering
│   └── EDA.ipynb                 # Statistical analysis and visualization
├── .gitignore                    # Environment, checkpoint, and CSV ignore rules
├── requirements.txt              # Core dependencies
└── README.md