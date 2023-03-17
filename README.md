# Data Cleaning
> Data cleaning is an essential step in the process of preparing data for analysis. It involves identifying and correcting or removing errors, inconsistencies, and inaccuracies in the data to ensure that it is accurate, complete, and consistent. 
In this repository, I have tried to solve the problems related to data cleaning through examples. This is the result of Kaggle exercises for data cleaning course.

## Contents
- Handling Missing Values
> Handling missing values is an important step in data cleaning and preparation in machine learning. Missing values can occur due to a variety of reasons such as data entry errors, system malfunctions, or incomplete data. It is important to handle missing values in a way that does not negatively impact the accuracy of the machine learning model.
- Scaling and Normalization
> Scaling and normalization are two important techniques used in machine learning to transform the features of a dataset. These techniques are used to bring the features of a dataset onto a similar scale, which can help improve the performance of many machine learning algorithms.
Scaling is used to change the range of values of a feature to a specific range. There are various methods of scaling, but the most common ones are Min-Max scaling and Standard scaling. Min-Max scaling rescales the feature to a range between 0 and 1, while Standard scaling rescales the feature to have a mean of 0 and a standard deviation of 1.
Normalization, on the other hand, is used to change the shape of the distribution of the feature. Normalization is commonly used when the data is not normally distributed. The most common method of normalization is Z-score normalization, which is also known as Standardization. Z-score normalization transforms the feature so that it has a mean of 0 and a standard deviation of 1.
- Parsing Dates
> Parsing dates is an important step in data preprocessing that involves converting date and time data in various formats into a standardized format that can be used for analysis. This is a crucial step in many machine learning and data science projects, as date and time data is often a key feature used in predictive models or in identifying patterns over time.
There are many different date and time formats that can be found in datasets, such as ISO format (YYYY-MM-DD), month/day/year format (MM/DD/YYYY), and more. Parsing these dates into a standardized format can be done using various Python libraries, such as pandas and datetime.
- Character Encoding
> Character encoding is the process of converting characters into codes that can be used in computers. In other words, it is the representation of text in binary format. Character encoding is necessary because computers only understand binary code, and therefore, any text or characters have to be converted to binary format before they can be processed by the computer. There are various character encoding standards, such as ASCII, Unicode, and ISO 8859, among others. The most commonly used encoding system is Unicode, which supports characters from almost all languages in the world. It provides a unique code point for each character, making it possible to represent any language using a single encoding system.
- Inconsistent data
> Inconsistent data refers to data that is not uniform or consistent within a dataset. This can be due to a variety of reasons such as human error, data entry mistakes, formatting differences, or changes in the data over time. Inconsistent data can cause issues with data analysis and can result in incorrect or biased results.
Cleaning inconsistent data involves identifying and resolving errors or discrepancies within the dataset. This can be done through various techniques such as standardizing data formats, correcting typos and misspellings, and removing duplicates or erroneous data points.
It is important to address inconsistent data in order to ensure accurate and reliable analysis results, as well as to maintain the integrity of the dataset for future use.

## Getting Started
> ### Installation
Install the required libraries using pip:
```Python
pip install pandas numpy matplotlib fuzzywuzzy chardet mlxtend seaborn matplotlib
```
## Usage
> Clone this repo and run the Data-Cleaning.ipynb

## Acknowledgement
[Kaggle Data Cleaning](https://www.kaggle.com/learn/data-cleaning)

## License 
[MIT License](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)
