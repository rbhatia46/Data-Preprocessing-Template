# Data-Preprocessing-Template
This repository includes all the Data Preprocessing required before using a dataset on a Machine Learning Model.

***

**This template might need some minor changes working with some other dataset. This code works fine with the given Data.csv file. Therefore, it 
is recommended to understand what this code does to use it for your own Machine Learning Models.**

***

## Libraries Used :
* Numpy
* Pandas
* Matplotlib (imported but not used in Data Preprocessing anywhere in this template)
* Scikit-Learn

## When to use which template :
There are 4 templates given in this repository and you need to choose which one to use in your situation, depending on the context.

* **data_preprocessing_template.py** : You can use this for all Machine Learning models(of course after those minor changes according to your dataset) and this is the most basic and simple template and the
bare minimum you will need.

* **missing_data_template.py** : You should use this when your training data has some missing values. Again, you will need mimnor changes depending 
upon your training data.

* **categorical_data_template.py** : Use this whenever you have categorical data. For example, in this Data.csv, you have Countries as a Categorical Data.

* **categorical_and_missing_data_template.py** : Use this when you have both Categorical and missing data in your dataset.

