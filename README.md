# Time Series Forecasting with Transformer Neural Network

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/github/license/rezaAdinepour/Time-Series-Forecasting)](LICENSE)

## Overview

This repository contains the code for **Time Series Forecasting** using a **Transformer Neural Network**. Transformers, originally introduced for Natural Language Processing (NLP) tasks, have shown great potential in modeling time series data. In this project, we use a transformer model to predict future values of a time series dataset. 

This implementation is highly modular, making it easier to adapt for various time series datasets and forecasting scenarios.

## Features

- **Transformer Architecture**: Leverages self-attention mechanisms to capture long-range dependencies in time series data.
- **Customizable**: Easily adaptable to different types of time series data.
- **Data Preprocessing**: Efficient data preprocessing pipeline with support for multiple time series datasets.
- **Visualization**: Plots actual vs predicted time series to analyze model performance.
- **Hyperparameter Tuning**: Simple interface for adjusting key model parameters like learning rate, number of layers, and attention heads.

## Demo

A sample of the output showing actual vs predicted values using the Transformer model:

![Forecast Example](./images/sample_plot.png)

## Repository Structure

```plaintext
.
├── data/                   # Folder to store input datasets
├── models/                 # Saved models after training
├── notebook/               # Jupyter notebook for development and experimentation
├── images/                 # Directory for saving plots and model visualization
├── utils.py                # Utility functions for preprocessing and model evaluation
├── transformer_model.py    # Transformer model architecture
├── requirements.txt        # Python dependencies
└── README.md               # Project overview
