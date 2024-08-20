# Time Series Forecasting Using Transformer Neural Networks

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/github/license/rezaAdinepour/Time-Series-Forecasting)](LICENSE)


## 📜 Overview

This project demonstrates the application of **Transformer neural networks** for **time series forecasting**. Originally designed for Natural Language Processing (NLP), Transformers are proving to be highly efficient in understanding the dependencies and patterns in sequential data such as time series. This repository contains the full implementation, training, and evaluation of a Transformer-based model designed to predict future values based on past sequences.

## 🔥 Key Features

- **Transformer Model**: Implements a custom Transformer architecture specifically designed for time series data.
- **Attention Mechanism**: Exploits the self-attention mechanism to capture both short-term and long-term dependencies.
- **Scalability**: Capable of handling large time series datasets.
- **Visualization**: Visualizes the actual vs predicted time series values.
- **Performance Metrics**: Provides detailed performance metrics, including MAE, MSE, and RMSE.

## 🛠️ Installation

To run the project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/rezaAdinepour/Time-Series-Forecasting.git
cd Time-Series-Forecasting
pip install -r requirements.txt
```



## Repository Structure

```plaintext
.
├── data/                   # Folder to store input datasets
│   ├── boeing.csv          # Time series dataset 1
│   ├── facebook.csv        # Time series dataset 2
│   └── jp_morgan.csv       # Time series dataset 3
├── model/                  # Folder containing the saved model
│   └── time_forecasting_transformer.pth           # Trained transformer model
├── src/                    # Source folder with code and notebook
│   └── main.ipynb          # Jupyter notebook for training and forecasting
├── images/                 # Directory for saving plots and model visualization
├── requirements.txt        # Python dependencies
└── README.md               # Project overview
```
