# Advanced Monitoring and Drift Analysis for Insurance Risk Models

## Objective

This project develops an advanced monitoring and drift analysis pipeline for insurance fraud models, designed to ensure long-term model reliability and operational value. The pipeline enables data science and business teams to track model performance and feature stability over time.

## Key Features

- Built a monitoring pipeline achieving 81% accuracy and 0.52 log loss on the fraud model, with batch-wise AUC stability ranging from 0.93 to 0.99.
- Delivered clear analytical insights on evolving feature behavior by detecting drift across 4 key features (including total_claim_amount and injury_claim) using KS tests.
- Conducted prediction drift analysis, comparing fraud probability distributions across simulated production batches to monitor model calibration and output stability.
- Established batch-wise performance tracking (AUC: 0.93–0.99, Accuracy: 94%–99%) to support best practices in ML operations and inform strategic fraud detection workflows.

## Tech Stack

- Python  
- XGBoost  
- Scikit-learn  
- SciPy  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## Data

- Insurance claims dataset (~1000 records, 45 columns)
- Customer demographics dataset
- Simulated external risk score
- Simulated time-based batches for monitoring

## Outcome

This project demonstrates how advanced monitoring and drift analysis can support insurance teams in:

- Tracking model performance and calibration over time
- Detecting feature and prediction drift early to maintain model reliability
- Informing strategic decisions in fraud detection and risk management workflows
