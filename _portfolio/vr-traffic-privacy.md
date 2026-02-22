---
title: "Inferring VR User Activity from Encrypted Network Traffic"
collection: portfolio
permalink: /projects/vr-traffic-privacy/
---

## Overview

This project investigates **privacy leakage in virtual reality (VR) systems**, showing that sensitive user activities can be inferred **purely from encrypted network traffic metadata**, without access to payloads or application internals.

As VR systems become widely deployed, understanding their privacy risks is critical. This work demonstrates that encrypted traffic alone can expose user behavior patterns at high accuracy.

---

## Problem

VR headsets continuously transmit encrypted data. While payload encryption protects content, **traffic patterns themselves leak information**.

Key questions:
- Can attackers identify which VR application is running?
- Can user activities (walking, object manipulation, speaking, flying) be inferred from traffic metadata alone?
- How robust are these inferences across sessions and noise?

---

## Approach

- Collected encrypted traffic from **25 VR applications** running on the Meta Quest Pro
- Extracted **statistical and temporal features** (packet sizes, inter-arrival times, burst patterns)
- Trained classical ML models (Random Forest, Decision Trees, MLP)
- Evaluated robustness under **temporal drift and noisy conditions**

---

## Results

- **92.4% accuracy** identifying VR applications  
- **~91% accuracy** identifying fine-grained user activities  
- Strong generalization across sessions and users  
- Demonstrated significant privacy risks despite encryption

---

## Contributions

- First large-scale empirical demonstration of VR activity inference via encrypted traffic
- Robust evaluation under realistic noise and session variability
- Clear implications for privacy-aware VR system design

---

## Tools & Methods

- Wireshark, Python
- Scikit-learn, PyTorch
- Feature engineering & robustness analysis
- Confusion matrices, temporal drift evaluation

---

## Publication

Accepted at **IEEE AIoT 2025**  
*“I Know What You Did Last Summer: Identifying VR User Activity Through VR Network Traffic”*
