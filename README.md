# Beyond Accuracy: A Multi-Dimensional Green AI Framework for SMS Spam Detection

This repository provides the official implementation and experimental setup for evaluating SMS Spam Detection through the lens of Green AI. Unlike traditional studies that focus solely on accuracy, this framework analyzes the trade-offs between predictive performance, operational efficiency, and environmental impact.

##  Key Highlights
* **Multi-Model Analysis:** Comparison of 10 different architectures, including Classical ML, Ensemble methods, and Deep Learning (Transformers).
* **Green Metrics:** Real-time tracking of **CO₂ emissions** and **energy consumption** using CodeCarbon.
* **Hardware Efficiency:** Evaluation of p95 latency (95th percentile latency), memory footprint, and model size.
* **Decision Matrix:** A decision matrix for selecting models based on deployment scenarios (Mobile, IoT, Cloud).

##  Evaluation Metrics
We go beyond F1 and MCC scores to include:
* **Environmental:** Energy (kWh) and Carbon footprint (kg).
* **Operational:** Latency (ms), Model Size (MB), and RAM Usage (MB).

##  Model Selection Guide
Based on our findings, we categorize models by use-case:
* **Low-Resource (IoT/Edge):** Naive Bayes & LR (Lowest carbon footprint).
* **Balanced (Mobile):** XGBoost (High performance with minimal lag).
* **High-End (Cloud):** DistilBERT (Maximum accuracy, high resource demand).

