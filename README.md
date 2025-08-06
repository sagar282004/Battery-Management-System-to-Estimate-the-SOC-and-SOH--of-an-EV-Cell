Battery State of Charge (SoC) Estimation Using Machine Learning

Project Overview

This project implements battery State of Charge (SoC) estimation using advanced machine learning techniques. The aim is to develop robust predictive models that estimate the SoC of lithium-ion battery cells based on available electrical measurements like voltage, current, and temperature, along with extracted electrochemical impedance spectroscopy (EIS) features when applicable.

You will find a complete pipeline from data loading, feature engineering, model training, validation, and visualization. The project covers datasets from publicly available benchmark sources such as the NASA Battery Dataset and the Mendeley Battery Dataset, along with custom experimental fresh and aged cell data.

Key Features:

 1. Efficient data loading and preprocessing for multiple battery datasets (NASA, Mendeley, custom experimental data).

 2. Robust feature engineering including voltage, current, temperature, and electrochemical impedance features.

 3. Machine learning modeling using proven regressors like Random Forest and Gradient Boosting for SoC estimation.

 4. Model evaluation and visualization with cross-validation metrics and actual vs predicted SoC plots.

 5. Modular and extensible pipeline for easy adaptation to new datasets or extension to SoH estimation.


Results:

* Achieved competitive SoC estimation errors (CV RMSE ~0.02-0.03), demonstrating strong model performance.

* Gradient Boosting Regressor consistently outperformed Random Forest and Linear Regression in cross-validation tests.

* Visualizations and residual analyses help fine-tune models further.



