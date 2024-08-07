# Celebal_Internship
Includes all the assignments and project.

## WEEK-4 : Outlier Handling with Standardization and Min-Max Scaling
This repository contains Python code that demonstrates how to handle outliers in a dataset using two different scaling methods: Standardization (Z-score normalization) and Min-Max scaling. It includes examples using a dataset from Seaborn's built-in datasets.

#### CONTENTS
- [Overview](#overview)
- [Dependencis](#dependencies)
- [Conclusion](#conclusion)

#### OVERVIEW
Outliers in datasets can significantly impact statistical analyses and machine learning models. This repository provides methods to replace outliers using two common scaling techniques:

Standardization (Z-score normalization):
Adjusts data to have a mean of 0 and a standard deviation of 1. 
Less sensitive to outliers compared to Min-Max scaling.

Min-Max Scaling:
Scales data to a fixed range, typically [0, 1].
Preserves the original distribution but can be sensitive to outliers.

The code includes functions to visualize boxplots before and after outlier replacement using both methods.

#### DEPENDENCIES
Ensure you have the following Python libraries installed:

-> seaborn
-> pandas
-> numpy
-> matplotlib
-> scikit-learn

#### CONCLUSIONS

![Sample Image](images/min_max_method.png)
![Sample Image](images/standard_method.png)

#### Standardization: 
Handling outliers using standardization (z-score) helps in scaling the data such that outliers are replaced with a threshold value, preserving the distribution of the data. This technique is useful for improving the robustness of statistical analyses and machine learning models that are sensitive to outliers.

#### Min-Max method:
Before Scaling:
Outliers are clearly visible beyond the whiskers in the boxplot.
Data shows high variance in values.

After Scaling:
Outliers are minimized and adjusted within the specified threshold range.
Data is normalized, making it easier to compare features on a common scale.

Using Min-Max Scaling effectively reduces the impact of outliers, ensuring that all features contribute equally to the analysis or machine learning model.

## WEEK-5 : Data Preprocessing





