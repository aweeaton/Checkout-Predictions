# Seattle Public Library System Book Check Out Predictions

### Summary
Beginning with over 35 Gigabytes of data, we predict which books will be predicted over the next month. This is a binary classification problem, where we utilized PySpark, Amazon EMR, and H2O. Through feature engineering and testing several different machine learning algorithms (including logistic regression, random forests, gradient boosted trees, and H2O's AutoML), we were able to achieve over 0.91 ROC AUC and 0.80 PR AUC.

### Data Processing - "Processing_Notebooks" Directory
* [Preprocessing.ipynb:](https://github.com/aweeaton/Checkout-Predictions/blob/master/Processing_Notebooks/Preprocessing.ipynb) Converts CSV data to HDFS .parquet files and hosts them on Amazon S3. 
* [Feature_Engineering.ipynb:](https://github.com/aweeaton/Checkout-Predictions/blob/master/Processing_Notebooks/Feature_Engineering.ipynb) Creates new features, splits a training and testing set, and writes HDFS .parquet files.

### Machine Learning - "ML_Notebooks" Directory
* [Final_Algorithms.ipynb:](https://github.com/aweeaton/Checkout-Predictions/blob/master/ML_Notebooks/Final_Algorithms.ipynb) Tests several machine learning classifiers with AUC ROC and AUC PR as validation metrics. 
* [Visualizations.ipynb:](https://github.com/aweeaton/Checkout-Predictions/blob/master/ML_Notebooks/Visualizations.ipynb) Plots EDA and some of the results from our models.

### Team
[Andrew Eaton](https://github.com/aweeaton)

[Shishir Kumar](https://github.com/ShishirKumar93)
