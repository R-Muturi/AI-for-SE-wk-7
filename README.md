# COMPAS Fairness Audit — README

This repository contains a simple fairness audit of the COMPAS Recidivism dataset.

## Contents
- `compas_fairness_audit.ipynb` — Jupyter notebook performing a racial bias analysis.
- `visuals/` (optional) — stores generated bias plots.
- `requirements.txt` (optional) — list of dependencies.

## What the Notebook Does
- Loads the COMPAS dataset.
- Computes false positive rate (FPR) for African-American vs Caucasian defendants.
- Plots FPR disparities.

## How to Run
1. Install required libraries:
   ```bash
   pip install pandas matplotlib
   ```
   If you want to use AIF360:
   ```bash
   pip install aif360
   ```
2. Open the notebook:
   ```bash
   jupyter notebook compas_fairness_audit.ipynb
   ```

## Purpose
This analysis is part of an AI Ethics assignment to demonstrate understanding of fairness metrics and bias detection in real-world datasets.

---
Simple, clear, and suitable for GitHub.
