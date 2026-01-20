# Structured EHR Modeling - RA Self-Study Guide

This guide is a step-by-step checklist for students to self-learn structured EHR modeling.

## Step 0: Setup and access
1. Get OSC access and a working Python environment.
2. Create a project folder structure:
   - `data/` (no raw data in repo)
   - `experiments/`
   - `reports/`
3. Read dataset access rules and complete any required training/DUA.

## Step 1: Learn the data
1. Choose one dataset (MIMIC-III or MIMIC-IV recommended).
2. Write a short dataset summary:
   - Data source, population, and time range.
   - Available tables (admissions, labs, meds, notes).
3. Record cohort statistics:
   - Number of patients, visits, and encounters.
   - Basic demographics and label distribution.

## Step 2: Run baseline tasks in PyHealth
1. Pick 4 tasks from PyHealth (mortality, readmission, LOS, drug rec).
2. For each task, create a folder under `experiments/` and log:
   - Task definition and target label.
   - Features and time window used.
   - Baseline model results (AUC, AUPRC, F1).
3. Summarize what worked and what did not.

## Step 3: Analyze results
1. Compare model performance across tasks.
2. Explain why some models work better (data size, features, noise).
3. Identify top predictive features and plausible clinical reasons.

## Step 4: Paper reproduction
1. Choose a recent clinical prediction paper.
2. Reproduce the main experiment with a clear protocol:
   - Dataset, cohort, task, metrics.
   - Training setup and evaluation.
3. Compare your results to the paper and explain gaps.

## Step 5: Deliverables checklist
- `reports/dataset_summary.md`
- `reports/task_results.md`
- `reports/paper_repro.md`
- `experiments/` with scripts and logs
