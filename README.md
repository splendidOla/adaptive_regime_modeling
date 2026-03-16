# adaptive_regime_modeling
Adaptive Regime-Based Rolling Window Algorithm for Retail Forecasting and Structural Change Detection

Official Implementation: Structural Change Detection
This repository contains the Python implementation of the Adaptive Regime-Based Rolling Window Framework, as presented in the paper "Adaptive Regime-Based Rolling Window Algorithm for Retail Forecasting and Structural Change Detection".

Traditional forecasting models often rely on fixed temporal windows (e.g., 30-day rolling averages), which fail to capture structural breaks in volatile environments. This framework introduces a dynamic approach that identifies "Regimes" based on statistical shifts, ensuring that forecasting models adapt to promotions, holidays, and market shocks in real-time.

🚀 Key Features
1. Hybrid Detection Engine: Combines Z-Score (point-based) and CUSUM (trend-based) algorithms for robust structural break detection.
2. CSI Metric: Introduces the Coefficient Stability Index, a novel metric used to quantify the reliability and stability of predictors within a specific regime.
3. Benchmarking: Includes integration with the PELT (Pruned Exact Linear Time) algorithm for offline changepoint validation.
4. Case Study: Complete analysis pipeline for Store 7 retail sales data.
