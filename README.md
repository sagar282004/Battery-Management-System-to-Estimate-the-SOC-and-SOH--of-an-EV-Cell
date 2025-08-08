Battery State of Charge (SoC) & State of Health (SoH) Estimation Using Machine Learning

Project Overview
This project develops a data-driven pipeline to estimate the State of Charge (SoC) and State of Health (SoH) of lithium-ion batteries. It combines experimental datasets—including fresh and aged cells, NASA’s public data, and Mendeley’s EIS dataset—with advanced feature engineering and machine learning models for accurate prediction of battery health metrics.

The pipeline leverages voltage, current, temperature, internal resistance, and the Open Circuit Voltage (OCV) vs. SoC curve to enhance prediction robustness.

Key Features
* Multi-Dataset Integration: Processes diverse battery datasets for comprehensive analysis.

* Advanced Feature Engineering: Includes derivatives, power calculations, internal resistance smoothing, and OCV-based SoC initialization.

* Machine Learning Models: Implements Random Forest, Gradient Boosting, Linear Regression, and Decision Trees, with Random Forest showing top performance for SOH.

* Data Exploration & Visualization: Extensive plots including time-series, scatter, distribution, residuals, and feature importance.

* Modular and Reproducible: Clear step-by-step code for easy reproduction and extension.

Usage
* Clone the repo and install dependencies.

* Prepare dataset directories and update paths.

* Run notebooks or scripts for SoC/SOH estimation.

* Analyze visualizations and model performance metrics.

