Electrochemical Impedance and Incremental Capacity Analysis with Machine Learning
This project involves simulating and analyzing Electrochemical Impedance Spectroscopy (EIS) data, performing Incremental Capacity Analysis (ICA), and building a machine learning model to predict real impedance using synthetic EIS data.

Table of Contents
Objective
Features
Dataset
Requirements
Setup Instructions
Project Structure
How to Run the Notebook
Results
Contact
Objective
The primary goal of this assignment is to:

Simulate synthetic EIS data for batteries.
Analyze battery performance through 3D visualization and ICA.
Train a machine learning model (Gradient Boosting Regressor) to predict real impedance based on synthetic data.
Evaluate the model's performance using RMSE and MAE.
Features
Simulation of synthetic EIS data with realistic ranges.
Visualization of EIS data in 3D.
Incremental Capacity Analysis (ICA) for charge and discharge cycles.
Visualization of ICA peaks over aging cycles.
Gradient Boosting Regressor implementation to predict real impedance.
Model evaluation metrics: RMSE and MAE.
Dataset
The dataset is simulated using Python’s NumPy library. The dataset includes:

Cycle Count: Number of aging cycles.
R(Z) (kΩ): Real impedance values.
Im(Z) (kΩ): Imaginary impedance values.
Requirements
To run this project, you need the following dependencies:

Python 3.7 or higher
Jupyter Notebook
Libraries:
numpy
pandas
matplotlib
scikit-learn


How to Run the Notebook
Ensure that you have installed all the dependencies listed in requirements.txt.
Open the EIS-ML-Modelling.ipynb file in Jupyter Notebook.
Execute all cells sequentially to:
Simulate synthetic EIS data.
Visualize EIS data in 3D.
Perform Incremental Capacity Analysis.
Train and evaluate the Gradient Boosting Regressor model.
Results
Model Evaluation Metrics:
Root Mean Squared Error (RMSE): 1.1009
Mean Absolute Error (MAE): 0.8954
Visualization Outputs:
3D Scatter Plot of EIS Data.
ICA Charge and Discharge Curves.
ICA Peaks over Aging Cycles.
Feature Importance Plot from the Gradient Boosting Regressor.
Actual vs Predicted Impedance Plot.
Contact
For any questions or feedback, feel free to reach out:
Name: Harsh Kumar Singh
Email: [your-hk43580@gmail.com.com]
GitHub: https://github.com/harsh43580

