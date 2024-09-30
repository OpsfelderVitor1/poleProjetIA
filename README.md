# Predictive Maintenance and Cost Optimization Project

## Overview
This project implements predictive maintenance models using machine learning techniques and cost analysis. It aims to predict Remaining Useful Life (RUL) of machines and optimize maintenance strategies to minimize operational and failure costs. The key components include data preparation, model training with early stopping, and cost sensitivity analysis.

## Key Features
- **Data Preparation**: Handles time-series data from machine sensors to create input features and corresponding RUL labels.
- **Model Training**: Includes training of machine learning models with early stopping criteria.
- **Cost Sensitivity Analysis**: Visualizes optimal costs for different combinations of failure and operational costs.

## How to Use
1. Clone the repository.
2. Install dependencies (e.g., `torch`, `seaborn`, `pandas`, `numpy`, `matplotlib`).
3. Run the script to prepare data, train models, and generate cost analysis heatmaps.

## Dependencies
- PyTorch
- NumPy
- Pandas
- Seaborn
- Matplotlib

## File Structure
- `poleprojet.py`: Main script for data preparation, model training, and cost analysis.
- `README.md`: This file, explaining the purpose and usage of the project.

## Training the Model
The model is trained using PyTorch, with early stopping to avoid overfitting. The training data consists of time-series features extracted from machine sensor data. The Remaining Useful Life (RUL) is used as the target variable.

## Cost Sensitivity Analysis
The cost analysis section of the project generates heatmaps to visualize the optimal maintenance cost and the proportion of engines replaced during their lifecycle. The heatmaps compare different values of operational and failure costs.

## Running the Project
To run the project, execute the script `poleprojet.py`. Ensure that all dependencies are installed and the required data is loaded into the correct format.

## License
This project is open-source and free to use.
