# Metrics-from-scratch
 Performance Metrics from Scratch in Python

This project implements a complete metrics evaluation framework from scratch, without relying on libraries like `sklearn.metrics`. It includes the computation of:

- Confusion matrix components (TP, FP, TN, FN)
- Performance metrics (TPR, FPR, FNR, TNR, Precision, Recall)
- Visualization of:
  - ROC Curve
  - Precision-Recall Curve
  - DET Curve
  - Error Rate Curve
  - Equal Error Rate (EER)

---

## 🧠 Motivation

The goal of this project is to understand the inner workings of performance metrics used in binary classification systems, particularly in:
- Speaker recognition systems
- Biometrics verification systems
- Any task where threshold-based binary decisions are critical

Instead of using external metric functions, we compute everything manually using `numpy`, `matplotlib`, and basic Python.

---
