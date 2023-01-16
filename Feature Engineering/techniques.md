# Feature Engineering Techniques

Imputation

* Identify the columns having significant amount of missing values with respect to the total number of data sets.
* Then discarded the columns containing 90% of null values.
Handle the missing values for the rest of the columns as follows.
    * Null values in the columns with categorical variables are substituted by the most frequent value in the relevant column.
    * Null values in the columns with continuous variables are substituted by the median value of the relevant column.