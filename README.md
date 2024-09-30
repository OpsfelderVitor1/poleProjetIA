# Predictive Maintenance for Turbofan Engine

## Overview
This project applies predictive maintenance techniques for turbofan engines using machine learning models. The main objective is to predict the Remaining Useful Life (RUL) of engine components and optimize maintenance schedules to reduce operational and failure costs. This project was developed as part of the Pôle Projet course, Groupe 08.

## Project Members
- Lucas Fernandes Martins
- Vitor Opsfelder Estanislau
- Eliott Binard
- Klara Juliette Tjernström

## Clients
- MathWorks
- CentraleSupélec
- Utrecht University

## Key Features
- **Predictive Maintenance**: Uses sensor data from turbofan engines to predict their Remaining Useful Life (RUL).
- **Machine Learning Models**: Implements various machine learning algorithms such as XGBoost and Neural Networks for time-series forecasting.
- **Cost Analysis**: Visualizes optimal maintenance costs based on failure and operational cost scenarios using heatmaps.

## How to Run
1. Clone the repository and open the Jupyter notebook `poleProjet.ipynb`.
2. Install the required Python libraries such as `feature-engine`, `xgboost`, `pandas`, and `matplotlib`.
3. Run the notebook cells sequentially to reproduce the results.

## Dependencies
- Feature-engine
- XGBoost
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Involved
1. **Data Preparation**: Preprocesses sensor data to generate features for model training.
2. **Model Training**: Trains predictive models to estimate the RUL of turbofan engines.
3. **Cost Sensitivity Analysis**: Generates heatmaps to analyze the trade-off between operational and failure costs for different maintenance strategies.

## License
This project is free to use for educational purposes.
