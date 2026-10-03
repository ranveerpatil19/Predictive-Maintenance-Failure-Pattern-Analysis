# Predictive Maintenance System Using LSTM Model

## Introduction
This project aims to develop a predictive maintenance system for industrial machinery using Long Short-Term Memory (LSTM) neural networks. The goal is to accurately predict machinery failures, enabling timely maintenance and reducing operational disruptions and costs.

## Project Summary
The project utilizes time-series forecasting techniques with LSTM models to predict machinery failures. The dataset used is sourced from [Kaggle - Microsoft Azure Predictive Maintenance](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance). The model is trained to predict when a machine is likely to fail based on sensor data and operational settings.

## Features
- **Data Analysis and Visualization**: Understand and visualize the dataset.
- **Data Preprocessing**: Clean and prepare data for modeling.
- **Feature Engineering**: Create meaningful features for the model.
- **Model Training and Evaluation**: Train and evaluate the LSTM model.

## Installation Guide

### Prerequisites
- Python 3.6+
- Git

### Steps

1. **Clone the Repository**
    ```sh
    git clone https://github.com/NirajBhakhar/Predictive-Maintenance-System-Using-LSTM.git
    cd Predictive-Maintenance-System-Using-LSTM
    ```

2. **Set Up Virtual Environment**
    ```sh
    python -m venv .venv
    ```

3. **Activate Virtual Environment**
    - On Windows:
      ```sh
      .venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```sh
      source .venv/bin/activate
      ```

4. **Install Required Packages**
    ```sh
    pip install -r requirements.txt
    ```

## Usage

- Open the Jupyter notebook in the `notebooks/` directory to explore data analysis and preprocessing steps.

## Results

The LSTM model was evaluated using Mean Squared Error (MSE). On validation data, it achieved a MSE of 0.0209, accurately capturing trends despite some fluctuations. On testing data, the MSE was higher at 0.0380, indicating increased prediction errors during anomalies.