# Pallet Forecasting Project

This repository contains a practical machine learning project focused on forecasting pallet-related trends and monitoring data quality over time. The project combines time-series forecasting with an interactive web interface and data drift analysis to provide a complete end-to-end demonstration of model usage and monitoring.

## Overview

The project includes notebooks for:
- Building and exploring a forecasting workflow for pallet data
- Creating an interactive Gradio application for generating forecasts
- Evaluating data drift and monitoring changes in input data with Evidently

## Project Goals

- Forecast future values from historical pallet data
- Provide an intuitive interface for interacting with the forecasting model
- Monitor data quality and detect drift over time
- Demonstrate how forecasting and model monitoring can work together in a simple workflow

## Repository Contents

- [pallet_forecasting.ipynb](pallet_forecasting.ipynb) — forecasting notebook with Gradio-based interaction
- [Evidently_practical_on_IRIS.ipynb](Evidently_practical_on_IRIS.ipynb) — notebook demonstrating Evidently dashboards and data drift monitoring
- [README.md](README.md) — project overview and usage guide

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn and Statsmodels
- Gradio for interactive visualization and model input
- Evidently for data drift and monitoring dashboards

## Getting Started

1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install gradio evidently pandas numpy matplotlib scikit-learn statsmodels jupyter
   ```
3. Open the notebooks in Jupyter Notebook or JupyterLab and run the cells sequentially.

## Usage

- Use [pallet_forecasting.ipynb](pallet_forecasting.ipynb) to explore the forecasting workflow and interact with the Gradio interface.
- Use [Evidently_practical_on_IRIS.ipynb](Evidently_practical_on_IRIS.ipynb) to understand how data drift monitoring can be visualized and assessed.

## Notes

This project is designed as an educational and demonstration-oriented workflow. It can be extended for more advanced forecasting pipelines, production monitoring, and deployment scenarios.
