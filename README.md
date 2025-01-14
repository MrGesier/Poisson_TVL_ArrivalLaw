# Poisson_TVL_ArrivalLaw
Arrival Law/Instatiation for TVL injection in a pool
# TVL Simulation with Log-Normal and Poisson Distributions

This repository contains a Python script to simulate Total Value Locked (TVL) trends over time using a combination of log-normal and Poisson distributions. The script reads TVL data from a CSV file, fits a log-normal distribution, and simulates daily user arrivals using a Poisson distribution. It calculates both daily and cumulative TVL, providing visualizations with dual y-axes.

## Features

- **Log-Normal Fitting**:
  - Fits a log-normal distribution to the provided TVL data.
- **Poisson User Simulation**:
  - Simulates daily user arrivals over 365 days for different Poisson `lambda` values (e.g., 2, 4, 32, 128).
- **TVL Simulation**:
  - Generates TVL values for each user based on the fitted log-normal distribution.
  - Aggregates daily TVL and calculates cumulative TVL.
- **Visualizations**:
  - Plots daily and cumulative TVL with dual y-axes for clear trend visualization.

## Requirements

The script requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`

Install the required dependencies with:
```bash
pip install -r requirements.txt
