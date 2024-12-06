SGD, MLP Regression, and Scalable Distance Mapping
This repository contains exercises exploring:

Implementing Stochastic Gradient Descent (SGD) for logistic regression.
Using an MLP for time-series interpolation and extrapolation.
Efficient computation of Euclidean distance maps.
Exercises Overview
Part 1: Logistic Regression with SGD
Manually implement SGD to optimize logistic regression parameters (β1, β2) without using built-in optimizers. The goal is to minimize the negative log-likelihood for synthetic data.

Part 2: Time-Series Regression with MLP
Interpolation: Train an MLP to predict (x(t), y(t)) from noisy time-series data for t ∈ [0, 20].
Extrapolation: Extend the model to predict beyond t = 20 up to t = 100.
Part 3: Distance Mapping
Compute Euclidean distances for sparse 2D points to a resolution tensor.
Extend this to batched inputs and make the function scalable for very high resolutions.
Usage
Clone the repository:
bash
Copy code
git clone <repository-url>
cd <repository-folder>
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Open the notebook:
bash
Copy code
jupyter notebook notebook.ipynb
Results
Logistic Regression: Visualize SGD optimizing parameters and the logistic function.
Time-Series: Accurate interpolation and extrapolation of (x(t), y(t)).
Distance Mapping: Efficient and scalable computation of distance maps.
