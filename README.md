# Repository Description:

The repository contains scripts for determining the optimal machine learning algorithm and its hyperparameters for a given dataset, tailored to either classification or regression tasks.

## Primary Scripts:
### Classification: For classification problems.
### Regression: For regression problems.

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
* Algorithm modification: In the sections responsible for loading (1.) and listing algorithms (4.), algorithms can be changed.
* Data modification: You can change the data used for analysis by using different datasets (2.).
* Adding more hyperparameters: If you want to experiment with more hyperparameters, you can add them to the hyperparameter section (8.) and test their impact on results.
* Other metrics: In the section where metrics are calculated (6.), you can add or modify existing metrics to tailor them to your needs.
* You can change the base metric used in GridSearchCV in the (9.).

### **Requirements:**
  * Python 3.10.6
  * Numpy 1.24.3
  * Pandas 2.2.2
  * Matplotlib 3.9.0
  * Scikit-learn 1.5.0
  * Xgboost 2.0.3
  * Catboost 1.2.5

**Install all at once:**
```
pip install numpy pandas matplotlib scikit-learn xgboost catboost
```

Author:
The project was created by [Cezary Łapiński / cezarylap] (https://github.com/cezarylap).


