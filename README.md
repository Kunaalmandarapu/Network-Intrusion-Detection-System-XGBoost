# Network-Intrusion-Detection-System-XGBoost
Two-stage ML-based Network Intrusion Detection System (Binary + Multi-class) using XGBoost with FastAPI backend and React dashboard for real-time and batch analysis

# 🔐 Network Intrusion Detection System (NIDS)

A production-style AI-powered Network Intrusion Detection System built using XGBoost, FastAPI, and React. The system detects malicious network traffic and classifies attack types using a two-stage machine learning pipeline.

---

## 🚀 Overview

This project goes beyond traditional ML models by implementing a complete end-to-end system:

- Binary classification (Normal vs Attack)
- Multi-class classification (10 attack categories)
- Real-time prediction via API
- Batch traffic analysis using CSV upload
- Interactive frontend dashboard

Dataset used: **UNSW-NB15 (257,673 samples, 10 classes)**

---

## 🧠 Architecture

1. **Phase 1 — Binary Detection**
   - Model: XGBoost
   - Accuracy: 95%
   - ROC-AUC: 0.991

2. **Phase 2 — Attack Classification**
   - Model: XGBoost (Multi-class)
   - Accuracy: 82%
   - Macro F1 Score: 0.60
   - Macro AUC: 0.967

---

## ⚙️ ML Pipeline

- Data preprocessing:
  - Missing value handling
  - Label encoding
  - Feature scaling

- Class imbalance handling:
  - SMOTE
  - SMOTETomek

- Evaluation metrics:
  - Accuracy
  - ROC-AUC
  - F1 Score
  - Confusion Matrix
  - Per-class recall

---

## 🖥️ Backend (FastAPI)

- REST APIs for:
  - Binary prediction
  - Multi-class classification
  - Batch CSV analysis

---

## 🎨 Frontend (React)

- Interactive dashboard with:
  - Real-time traffic prediction
  - Attack classification
  - Feature input (42 features)
  - Model performance visualization
  - Basic explainability (feature importance)

---

## 📊 Features

- Two-stage detection pipeline
- Real-time + batch processing
- Explainable predictions
- Full-stack integration (ML + API + UI)

---

## 📂 Project Structure
