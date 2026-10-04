Smart EV Range Prediction Simulation

Overview

A machine-learning-based simulation for predicting the remaining driving range of an Electric Vehicle (EV) using simulated battery, driving and environmental data. The simulation explores uncertainty-aware range estimation by generating prediction intervals instead of relying only on a single predicted value.

Objectives

1.Simulate EV operating conditions.
2.Predict remaining driving range using machine learning.
3.Generate prediction intervals using conformal prediction.
4.Evaluate prediction error and interval coverage.

Technologies Used
1.Python
2.Google Colab
3.NumPy
4.Pandas
5.Matplotlib
6.Scikit-learn

Methodology

1. Generated 5,000 synthetic EV trips with varying battery charge, battery health, temperature, speed, traffic, road slope,     HVAC usage and driving style.
2. Divided the data into training, calibration and testing sets.
3. Trained a Random Forest regression model to estimate remaining range.
4. Applied conformal prediction to construct 90% prediction intervals.
5. Evaluated prediction error and interval coverage on unseen test data.

Simulation Results

1.Simulated trips: 5,000
2.Test coverage: 90.4%
3.Average absolute error: 6.72 km
4.Average percentage error: 5.51%
5.Average interval width: 28.99 km

Limitations

This is a demonstration based on synthetic data and has not been validated with real EV sensor measurements or real-world driving trips. The results are specific to this simulation and do not reproduce the original case study's reported results.

Author
Navya C R
