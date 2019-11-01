# Databricks Logistic Regression and Pipelining Example

Based entirely on https://docs.databricks.com/applications/machine-learning/mllib/binary-classification-mllib-pipelines.html but using different data.

Some features of this Databricks Python code:

* Demonstrates pulling in a directory of `.parquet` files
* Some basic pipelines 
* One-hot encoding for categorical variables
* Using Logistic Regression within Databricks

# Requirements
You'll need a Databricks environment to run this Notebook. You can import it and change any file locations (e.g., the location of the `.parquet` files). You'll also need your own data, or you can use what I used:

https://github.com/bellevue-university/dsc650/tree/master/data/baby-names/names_classifier

The main file is the Jupyter Notebook, which was exported from Databricks. 
