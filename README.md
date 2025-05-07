# SARCOS Robot Inverse Dynamics - Performance Data

This repository contains JSON files storing the performance statistics for experiments conducted on the SARCOS dataset, as described in the paper: "Efficient Gaussian Process Regression and Comparative Analysis for Robot Inverse Dynamics on the SARCOS Dataset".

## Data Files

The following JSON files are included:

* **performance_statistics.json:** Contains performance statistics for the Linear Gaussian Process model.
* **performance_statistics_rbf.json:** Contains performance statistics for the Non-linear Gaussian Process model with the Radial Basis Function (RBF) kernel.
* **performance_statistics_sklearn_models_sub100.json:** Contains performance statistics for the scikit-learn models, evaluated on a subset of 100 data points.

##  Content of the JSON Files

Each JSON file contains a dictionary. The exact structure might vary slightly between files, but generally, you can expect key-value pairs representing performance metrics.  Common metrics might include:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R-squared ($R^2$) score
* Training Time
* Prediction Time

**Note:** For precise details on the contents of each JSON file, please refer to the paper or inspect the files directly.  The keys within the JSON files should correspond to the metrics reported in the paper.

##  Usage

These JSON files can be used to:

* Reproduce the performance analysis presented in the paper.
* Compare the performance of different Gaussian Process models and scikit-learn models on the SARCOS dataset.
* Visualize the performance metrics.
* Further analyze the results using your own scripts and tools (e.g., Python with `json` and data analysis libraries).
