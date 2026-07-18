# RUL Estimation and Health Monitoring of EV Batteries Using Deep Learning Models
**Remaining Useful Life Estimation for Lithium-Ion Batteries using CNN-LSTM architecture**

---

## 📖 Overview

Lithium-ion batteries are the backbone of modern Electric Vehicles (EVs), making accurate **Remaining Useful Life (RUL)** estimation essential for battery health monitoring, predictive maintenance, and ensuring operational safety.

Our work includes:

- 🔋 Remaining Useful Life (RUL) Estimation
- 📈 State of Health (SOH) Estimation
- 📉 Capacity Degradation Trends
- ⚡ Battery Performance Trends

Multiple Machine Learning and Deep Learning models are implemented and compared to identify the most effective approach for long-term battery prognostics.

---

## 🎯 Objectives

- Predict battery Remaining Useful Life.
- Monitor battery degradation over charging cycles.
- Compare traditional ML models with Deep Learning models.
- Analyze model performance using multiple evaluation metrics.
- Provide a scalable framework for Battery Management Systems (BMS).

---

# 📂 Dataset

The project uses the **NASA Lithium-Ion Battery Aging Dataset**, containing degradation data collected under controlled charge-discharge cycles.

Dataset includes:

- Capacity
- Voltage
- Current
- Temperature
- Charge Cycles
- Discharge Cycles
- Internal Resistance

Batteries used in this work:

- Battery 5
- Battery 6
- Battery 7
- Battery 18

---

# 🧠 Models Implemented

## Machine Learning

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor
- LightGBM

## Deep Learning

- Artificial Neural Network (ANN)
- Long Short-Term Memory (LSTM)
- CNN-LSTM Hybrid (Proposed Model)

---

# ⚙️ Workflow

```text
NASA Battery Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
SOH Calculation
        │
        ▼
Sequence Generation
        │
        ▼
Model Training
        │
        ▼
RUL Prediction
        │
        ▼
Performance Evaluation
```

---

# 📊 Features Used

- Capacity
- Voltage
- Current
- Temperature
- Cycle Count
- State of Health (SOH)
- Capacity Fade
- Remaining Cycles

---

# 📈 Evaluation Metrics

The following metrics are used to evaluate model performance:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)
- R² Score

---

# 📊 Results

The proposed deep learning architecture demonstrates significant improvements over traditional regression approaches by effectively learning temporal dependencies.

Example prediction plots:

- Capacity Degradation
- State of Health
- Remaining Useful Life
- Predicted vs Actual RUL
- Training & Validation Loss

---

# 📷 Sample Outputs

- Capacity vs Cycle Curve
- SOH Prediction
- RUL Prediction
- CNN-LSTM Training Curve
- Predicted vs Actual Comparison

*(Add screenshots here after uploading.)*

---

# 📚 Research Paper

This repository accompanies our research paper:

> **Remaining Useful Life Estimation and Health Monitoring of EV Battery Systems Using Deep Learning Models**

The paper presents:

- Battery degradation analysis
- Feature engineering methodology
- Machine Learning baseline models
- Proposed CNN-LSTM architecture
- Experimental evaluation
- Comparative performance analysis
- Future research directions

📄 **Paper Location**

```
paper/FinalDraft.pdf
```

---

# 🛠 Tech Stack

- Python
- TensorFlow/Keras
- Scikit-Learn
- XGBoost
- LightGBM
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

