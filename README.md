# Machine Failure Prediction Model

## Overview

This project involves predicting potential machine failures based on sensor readings, historical maintenance events, and operating conditions. The model outputs a probability score indicating the likelihood of failure occurring within a specified timeframe (e.g., 24 hours). It uses algorithms like Logistic Regression, Decision Trees, or Random Forests for interpretability and accuracy.

## Setup Instructions

### Prerequisites

To set up and use the model, ensure you have the following dependencies installed:

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for visualizations)
- Jupyter Notebook (optional, for easier testing)

### Installation

1. Clone the repository or download the project folder.
2. Install the necessary libraries using pip:

pip install pandas numpy scikit-learn matplotlib

# Model Components

- Sensor Data: Includes temperature, pressure, vibration, and operating conditions.
- Target Variable: The failure_within_24h column predicts whether a failure will occur within 24 hours.
- Model: The model is built using classification algorithms such as Logistic Regression, Decision Trees, or Random Forests.
- Features: Sensor data features like temperature, pressure, vibration, operating_condition, and historical_maintenance.
