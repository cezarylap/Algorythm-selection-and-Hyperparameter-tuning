# Repository Description:

This repository contains two scripts for comparing and optimizing machine learning algorithms on different datasets. The first script focuses on classification algorithms, while the second script addresses regression algorithms. Both scripts evaluate models with default hyperparameters, perform hyperparameter tuning to maximize a specific metric, and then compare the results.

## Repository Structure
### Classification.ipynb: Compares classification algorithms on a given dataset.
### Regression.ipynb: Compares classification algorithms on a given dataset.

## Features
* Default Hyperparameter Evaluation: Assess the performance of algorithms using default hyperparameters.
* Hyperparameter Tuning: Optimize hyperparameters to maximize a specific metric.
* Performance Comparison: Compare the results before and after hyperparameter tuning.

### Scripts Structure:
1. Importing necessary libraries.
2. Loading and splitting the data.
3. Data standardization.
4. List of algorithms.
5. Cross-validation parameters.
6. Functions to generate model metrics.
7. Generating metrics for default hyperparameters.
8. Defining hyperparameter grids for each algorythm.
9. Generating best hyperparameter sets based on specified metric using grid search.
10. Generating additional metrics using the best hyperparameter sets.
11. Formatting tables (Github does not display tables in formatted form).
12. Displaying the generated tables.

### Suggestions for editing the scripts:
* **Algorithm modification**: In the sections responsible for loading (1.) and listing algorithms (4.), algorithms can be changed. When adding a new algorithm, remember to add a set of hyperparameters (8.) to check their effect on the result.
* **Data modification**: You can change the data used for analysis by using different datasets (2.).
* Adding more **hyperparameters**: If you want to experiment with more hyperparameters, you can add them to the hyperparameter section (8.) and test their impact on results.
* Other **metrics**: In the section where metrics are calculated (6.), you can add or modify existing metrics to tailor them to your needs. You can also change the base metric used in hyperparameter GridSearchCV in the (9.).

### Installation
Clone the repository:
```
git clone https://github.com/cezarylap/ML-Algorithm-Optimization-Comparison
```
Install the required dependencies:
```
pip install -r requirements.txt
```
### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Author:
The project was created by [Cezary Łapiński / cezarylap] (https://github.com/cezarylap).


