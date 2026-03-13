# Beyond Accuracy: A Multi-Dimensional Green AI Framework

This repository contains the official implementation and data for evaluating **SMS Spam Detection** through the lens of **Green AI**. Unlike traditional studies that focus solely on accuracy, this framework analyzes the trade-offs between predictive performance, operational efficiency, and environmental impact.

##  Key Highlights
* **Multi-Model Analysis:** Comparison of 10 different architectures (Classical ML, Ensembles, and Transformers).
* **Green Metrics:** Real-time tracking of **CO₂ emissions** and **energy consumption** using CodeCarbon.
* **Hardware Efficiency:** Evaluation of p95 latency, memory footprint, and model size.
* **Decision Matrix:** A comprehensive guide for choosing models based on deployment scenarios (Mobile, IoT, Cloud).

##  Evaluation Metrics
We go beyond F1 and MCC scores to include:
* **Environmental:** Energy (kWh) and Carbon footprint (kg).
* **Operational:** Latency (ms), Model Size (MB), and RAM Usage (MB).

##  Model Selection Guide
Based on our findings, we categorize models by use-case:
* **Low-Resource (IoT/Edge):** Naive Bayes & LR (Lowest carbon footprint).
* **Balanced (Mobile):** XGBoost (High performance with minimal lag).
* **High-End (Cloud):** DistilBERT (Maximum accuracy, high resource demand).

