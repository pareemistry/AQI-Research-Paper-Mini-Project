# AQI-Research-Paper-Mini-Project

# 🌍 ST-MPFT: Spatio-Temporal Multi-Path Fusion Transformer for AQI Forecasting

## Overview

This project presents a deep learning framework for **Air Quality Index (AQI) forecasting** using a novel **Spatio-Temporal Multi-Path Fusion Transformer (ST-MPFT)** architecture. The model captures both temporal dependencies and spatial relationships between cities to improve multi-step AQI prediction.

## Features

* 📊 End-to-end AQI forecasting pipeline
* 🧹 Data preprocessing and feature engineering
* 🤖 Baseline models: VAR, XGBoost, BiLSTM + Attention, STGCN, Patch Transformer
* 🚀 Proposed **ST-MPFT** model
* 🎯 Hyperparameter tuning with Optuna
* 📈 Time-series cross-validation
* 📉 Multi-metric evaluation (MAE, RMSE, SMAPE, Macro F1)
* 🔬 Ablation studies for model validation
* 📊 Training curves and performance visualization

## Dataset

* **India City Air Quality Index Dataset (2015–2023)**
* Pollutants used:

  * PM2.5
  * PM10
  * NO₂
  * SO₂
  * CO
  * O₃

## Technologies

* Python
* PyTorch
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* Optuna
* Matplotlib

## Project Workflow

1. Data Loading & Preprocessing
2. Feature Engineering
3. Baseline Model Training
4. ST-MPFT Model Development
5. Hyperparameter Optimization
6. Cross-Validation
7. Final Model Training
8. Performance Evaluation
9. Ablation Study

## Results

The proposed **ST-MPFT** model demonstrates competitive performance by effectively learning spatial and temporal dependencies, outperforming conventional forecasting approaches on multiple evaluation metrics.

## Repository Structure

```
├── aqi-research-paper-mini-project.ipynb
├── README.md
└── requirements.txt (optional)
```

## How to Run

1. Download the AQI dataset.
2. Open the notebook in Kaggle or Jupyter Notebook.
3. Install the required dependencies.
4. Execute the notebook sequentially.
5. Train the model and evaluate the results.

## Future Work

* Graph Attention Networks (GAT)
* Dynamic graph learning
* Real-time AQI prediction
* Deployment using Streamlit or Flask
* Integration with weather and traffic data

## License

This project is developed for academic and research purposes.
