# F1 Race Outcome Prediction System

## Overview
This project predicts Formula 1 race outcomes using:
- Gradient Boosting Model (GBM)
- Monte Carlo Simulation
- Agentic AI Layer for scenario-based simulations

## Key Results
- Best Model: Gradient Boosting Regressor
- R²: 0.687
- RMSE: 7.50

## Key Insights
- Grid position strongly impacts finishing position (~0.63 correlation)
- Driver form and team performance are top predictors
- Weather has low direct impact but affects uncertainty

## Approach
1. Data Collection (FastF1 API)
2. Feature Engineering (18 features)
3. Model Training (GBM, XGBoost, LightGBM)
4. Monte Carlo Simulation (5000 runs)
5. Agentic AI Layer for scenario simulation

## Unique Contribution
- Natural language → simulation input
- AI-generated race insights
- Probabilistic race forecasting

## Example
"Simulate a chaotic wet race"
→ AI adjusts driver variability and outputs probabilities

## Tech Stack
Python, Pandas, Scikit-learn, XGBoost, LightGBM, FastF1

## Files
- `notebook/` → full analysis
- `report/` → detailed report

## Future Work
- LSTM for lap prediction
- Real-time simulation
- Reinforcement learning for pit strategy
