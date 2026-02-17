---
title: "Predictive Maintenance for Manufacturing Equipment"
excerpt: "Implementing an IoT-based predictive maintenance system using Deep Learning."
collection: projects
tags:
  - AI
  - Manufacturing
  - Deep Learning
  - Python
header:
  teaser: /assets/images/ai-teaser.jpg
---

## Problem Context
Unplanned downtime in a high-volume manufacturing line was causing significant production losses. Traditional preventive maintenance schedules were inefficient, leading to unnecessary component replacements or unexpected failures.

## Objective
To predict equipment failures at least 24 hours in advance, allowing for proactive maintenance and reducing downtime.

## Data Description
*   **IoT Sensors:** Vibration, temperature, and pressure readings sampled at 1Hz.
*   **Logs:** Historical maintenance logs and failure events.
*   **Volume:** 2TB of time-series data covering 12 months of operation.

## Methodology
1.  **Data Engineering:** Built a pipeline to ingest and preprocess streaming sensor data.
2.  **Feature Extraction:** Extracted time-domain and frequency-domain features (FFT) from vibration signals.
3.  **Modeling:** Trained an LSTM (Long Short-Term Memory) autoencoder to detect anomalies and predict Remaining Useful Life (RUL).

## Tools and Technologies
*   **Deep Learning:** TensorFlow/Keras, PyTorch
*   **Data Processing:** Apache Spark, Pandas
*   **Visualization:** Grafana, Matplotlib

## Results
*   **Accuracy:** Achieved an F1-score of 0.89 in predicting failure events.
*   **Downtime Reduction:** Reduced unplanned downtime by **22%** in the first quarter of deployment.
*   **ROI:** Estimated savings of $150k annually in maintenance costs.

## Impact
The system transitioned the maintenance strategy from reactive to predictive, improving Overall Equipment Effectiveness (OEE).

[<i class="fab fa-github"></i> View on GitHub](https://github.com/leogasis/project-repo)
