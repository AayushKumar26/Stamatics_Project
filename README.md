# Stamatics Time‑Series Forecasting Project
**Organized by Stamatics, Society of Department of Mathematics and Statistics, IIT Kanpur**  
**Timeline:** May 2024 – July 2024

An end‑to‑end exploration of time‑series analysis and forecasting, this project applies classical statistical methods and modern deep‑learning techniques to real‑world retail and sales datasets. Through a sequence of assignments and a capstone implementation, we:

- Decompose long‑term trends and seasonal patterns over a 13‑year period.
- Build ARMA/ARIMA models for point forecasts with uncertainty quantification.
- Model time‑varying volatility using ARCH/GARCH frameworks.
- Develop a neural forecasting system that automatically learns to prioritize key observations, boosting multivariate accuracy (ACF ≈ 0.8).

---

## 🎯 Project Objectives

1. **Understand** the components of time series (trend, seasonality, residuals) via interactive visualizations.
2. **Implement** statistical forecasting algorithms (ARMA, ARIMA) with confidence intervals for future retail sales.
3. **Analyze** and **forecast** volatility in financial return series using ARCH and GARCH models.
4. **Design** a deep‑learning pipeline that adapts attention‑style mechanisms to select influential time points, improving forecast performance on multivariate inputs.
5. **Demonstrate** reproducibility of results through fixed seeds, explicit logging, and structured directories.

---

## 📚 Repository Contents

- **Assignment Sections (3 folders):** Each assignment folder contains a detailed problem statement and complete solution notebooks covering:
  - **Assignment 1:** Time‑series decomposition and EDA.
  - **Assignment 2:** ARMA/ARIMA forecasting with model selection.
  - **Assignment 3:** ARCH/GARCH volatility modeling and backtesting.

- **Deep‑Learning Forecast:** Capstone notebook showcasing data preprocessing, model architecture, training, and evaluation.

- **Resources Folder:** All datasets (raw and processed), reference materials, slides, and helper scripts are stored here.

---

## 🗂 Presentation & Core Notebook

- **Project Presentation (PPT):** A comprehensive slide deck (`Resources/Time_Series_Presentation.pptx`) walks through the entire workflow:
  - Background and objectives of retail sales forecasting.
  - Data sources, cleaning steps, and exploratory visualizations.
  - Trend-seasonality decomposition examples with annotated plots.
  - Statistical modeling summaries (ARMA/ARIMA and ARCH/GARCH), including diagnostics and forecast examples.
  - Deep-learning model architecture, attention mechanism, and evaluation metrics.
  - Key insights, performance comparisons, and next-step recommendations.

- **Interactive Notebook (`Time_Series.ipynb`):** The primary Jupyter notebook consolidates code and narrative:
  - **Data Ingestion & Preprocessing:** Loading CSVs, handling missing values, normalization routines.
  - **Exploratory Analysis:** Time-series plots, rolling statistics, ACF/PACF computations.
  - **Model Implementations:** Step-by-step ARMA/ARIMA and ARCH/GARCH fitting with parameter tuning.
  - **Deep‑Learning Pipeline:** Defining the neural network, training loop, loss curves, and forecast visualization.
  - **Results & Discussion:** Tabulated metrics (MAPE, RMSE, ACF), residual analysis, and performance graphs.
  - **Reproducibility Notes:** Fixed seeds, environment setup, and directory structure pointers.

---

## 📂 Resources

All raw and processed data files, along with reference papers, presentation slides, and utility scripts, are uploaded in the `Resources/` directory for easy access and reproducibility.
