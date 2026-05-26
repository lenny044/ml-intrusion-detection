# ML-Based Network Intrusion Detection System

A machine learning project that detects network intrusions and cyberattacks using the NSL-KDD dataset. Compares Decision Tree and Random Forest classifiers.

## Problem Statement
Network administrators cannot manually monitor thousands of connections per second. This system automatically classifies network traffic as normal or malicious using machine learning.

## Dataset
- **NSL-KDD** — standard benchmark dataset for intrusion detection research
- 125,973 training samples | 22,544 test samples | 41 features
- Attack types: DoS, Probe, R2L, U2R (neptune, smurf, portsweep, nmap and more)

## Models & Results

| Model | Accuracy | AUC |
|-------|----------|-----|
| Decision Tree | 79.32% | 0.817 |
| Random Forest | 77.17% | 0.915 |

**Key Finding:** Decision Tree achieved higher raw accuracy, but Random Forest scored a significantly better AUC of 0.915 — making it more reliable for real-world deployment.

## Results Preview <img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/521fd2e3-5935-4376-a22c-8fac87ae6549" />
