# 🌦️ ClimateWins: Weather Conditions and Climate Change

### By [Your Name]

This project explores how **machine learning** can be used to predict weather conditions and identify signs of **climate change** across Europe. It was developed as part of the ClimateWins initiative.

---

## 🧭 Objective

ClimateWins aims to understand and predict how climate change affects weather patterns using historical European data.  
The project evaluates three supervised machine learning algorithms:

- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Artificial Neural Network (ANN)**

---

## 📊 Data Overview

- Source: [European Climate Assessment & Dataset Project (ECA&D)](https://www.ecad.eu/)
- 18 weather stations across Europe
- Data range: 1960–2022
- Features include: temperature, humidity, precipitation, wind speed
- Clean dataset (no missing values)

---

## ⚙️ Optimization

- Data optimized using **Gradient Descent** to minimize prediction error.
- Temperature and weather condition data were normalized and scaled before training.

---

## 🧠 Machine Learning Models

| Model | Description | Avg Accuracy | Notes |
|-------|--------------|---------------|-------|
| KNN | Groups new data based on similarity to neighbors | **89%** | Most accurate overall |
| Decision Tree | Splits data using feature thresholds | 46% | Requires pruning |
| ANN | Learns complex patterns via neural layers | 56% | Potential for improvement |

---

## 🌍 Findings

- KNN was the **most accurate model** for predicting pleasant weather days.
- Some weather stations (e.g., Sonnblick) showed near-perfect predictions, while others (e.g., Madrid) varied due to local climate patterns.
- Overfitting occurred in ANN and Decision Tree models.
- Machine learning shows clear potential for detecting climate change patterns.

---

## 🚀 Next Steps

- Fine-tune ANN parameters for better generalization.
- Incorporate unsupervised learning to find hidden climate trends.
- Expand dataset with more features (wind speed, radiation, etc.).
- Predict long-term climate change impacts.

---

## 🧩 Requirements

Create a `requirements.txt` with your Python libraries (example below):

