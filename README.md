# kalman_filters
This project implements a basic 2-state Kalman Filter using PyTorch tensors for financial time-series denoising and signal estimation.

The filter models stock prices using:

- Position (price)
- Velocity (price change)

and recursively performs:

1. Prediction step
2. Update step

to estimate smoother stock price trajectories from noisy market data.

## Features

- Kalman Filter implementation from scratch
- Built using PyTorch tensor operations
- Recursive prediction-update framework
- Stock price denoising
- Q parameter sensitivity analysis
- MSE and Pearson correlation evaluation
- Comparison with Moving Average filtering

## Concepts Covered

- State-space models
- Recursive Bayesian estimation
- Process noise covariance (Q)
- Measurement noise covariance (R)
- Kalman Gain
- Signal smoothing
- Time-series filtering

## Results

The project demonstrates how different values of Q affect:
- filter smoothness
- responsiveness
- denoising performance
using MSE-based sensitivity analysis.

## Future Improvements

-using optuna for tuning 
