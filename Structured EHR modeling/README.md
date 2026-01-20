# Structured EHR Modeling - RA Training

This track focuses on structured electronic health record (EHR) data and clinical prediction. The goal is to build solid data handling skills and reproduce baseline results with PyHealth.

## Learning objectives
- Understand common EHR datasets and data formats.
- Run and interpret standard clinical prediction tasks.
- Learn how to preprocess structured data and evaluate models.

## Training steps
1. OSC basics
   - Run a simple Python job on OSC.
   - Manage environments and file paths.
2. PyHealth basics
   - Select 4 interested built-in tasks (e.g., mortality, readmission) in [PyHealth](https://pyhealth.readthedocs.io/en/latest/api/tasks.html) and use the buit-in models to get the results.
   - For each task, summarize or explain:
     - Dataset source.
     - Cohort statistics (e.g., patient count, visits, demographics).
     - Label distribution and class balance.
     - Features used (codes, labs, demographics, time window).
     - Setup (e.g., how to define cohort, set the observation and prediction window).
     - Baseline models and performance (e.g., AUC, AUPRC, F1).
     - Short analysis: why a model performs better; which features help.
3. Paper reproduction
   - Reproduce following papers or any 3 papers in top ML/AI conferences this year.
   - [AgentMD: Empowering language agents for risk prediction with large-scale clinical tool learning](https://www.nature.com/articles/s41467-025-64430-x)
   - [BoxLM: Unifying Structures and Semantics of Medical Concepts for Diagnosis Prediction in Healthcare](https://openreview.net/forum?id=jIci8mGVeh)
   - [Multimodal Medical Code Tokenizer](https://openreview.net/forum?id=UaTrcei5Ba)
   - [SAFER: A Calibrated Risk-Aware Multimodal Recommendation Model for Dynamic Treatment Regimes](https://openreview.net/forum?id=7UqNM85dD6)
   - [Democratizing Clinical Risk Prediction with Cross-Cohort Cross-Modal Knowledge Transfer](https://openreview.net/forum?id=7dJfwHG3GN)

## Deliverables
- A short write-up describing the dataset, task, and evaluation metrics.
- Reproducible code and logs.
- A brief summary of what worked and what did not.
