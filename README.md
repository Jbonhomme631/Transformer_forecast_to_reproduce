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



## 📂 Repo Structure

```plaintext
.
├── data/                                          # Folder to store input datasets
│   ├── boeing.csv                                 
│   ├── facebook.csv                               
│   └── jp_morgan.csv                              
├── model/                                         # Folder containing the saved model
│   └── time_forecasting_transformer.pth           # Trained transformer model
├── src/                                           # Source folder with code and notebook
│   └── main.ipynb                                 # Jupyter notebook for training and forecasting
├── images/                                        # Directory for saving plots and model visualization
├── requirements.txt                               # Python dependencies
└── README.md                                      # Project overview
```


📊 Dataset

The datasets used for this project should be a univariate or multivariate time series dataset in `.csv` format. Ensure the dataset is properly formatted with a timestamp column (if applicable) and feature columns.

we use `facebook.csv` for train model and `boeing.csv` and `jp_morgan.csv` for validate model.
