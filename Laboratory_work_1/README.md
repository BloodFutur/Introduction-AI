# Laboratory work 1

This repository contains the code of my Artificial Intelligence course at the Kaunas University of Technology. 
It is the first laboratory work.

## Laboratory contents

The laboratory work is implemented in Python 3.6. The code is written in Jupyter notebooks. The dataset is named `IT_customer_churn.csv`.
This laboratory work focuses on the data preprocessing and exploratory data analysis.

### Choice of the dataset

I have chosen the dataset from the [Kaggle](https://www.kaggle.com/datasets/soheiltehranipour/it-customer-churn)website.
I have chosen this dataset because it is a good example of a real-world dataset. It contains a lot of features and it is a good example of a dataset that needs to be preprocessed before it can be used for machine learning.

### Task 1

Select a dataset to perform this and other laboratory works. Your choice must be approved by the tutor.

Dataset requirements:
- Numeric and categorical attributes must exist in the dataset.
- For a dataset, the number of records must be at least 500 and the number of attributes must be at least 8.

**Important**. The following tasks must be implemented programmatically using Python.

### Task 2

Peform dataset quality analysis.

For each countinous attribute, calculate the following:
- total number of values
- percentage of missing values,
- cardinality,
- minimum (min) and maximum (max) values,
- 1st and 3rd quartiles,
- average,
- median,
- Standard deviation.

For each categorical attribute, calculate the following:
- total number of values
- percentage of missing values,
- cardinality,
- mode
- frequency of the mode
- percentage of the mode
- second mode value
- frequency of the second mode
- percentage of the second mode

Compose a table to present each type of variable (countinous and categorical) and the corresponding statistics.


### Task 3

Draw histograms of attributes (recommended number of histogram bins is is defined by a formula: 1+3.22log_e(n)). Provide descruptions of the distribution and what you can conclude from the histograms.

### Task 4

Identify data quality issues: missing values, cardinality, outliers. Provide a plan for resolving the issues, which will be implemented programmatically.

### Task 5

Investigate relationships between attributes using visualizations. 

**For continuous type attributes**
- Using a scatter plot graph, provide several examples with strong linear attribute dependencies. and several examples with non-correlated attributes. Comment on the results.
- Provide SPLOM diagram (Scatter Plot Matrix)

**For categorical type attributes**
- Using the bar plot type diagram, give some examples of attribute dependencies. Comment on the results.
- Provide some examples of histograms and box plot diagrams depicting relationships between categorical and continuous attributes. Comment on the results.

### Task 6
Calculate the covariance and correlation values between continues attributes and graphically represent the correlation matrix. Comment on the results.

### Task 7
Perform data normalization and standardization.

### Task 8
Convert categorical attributes to numerical attribute.