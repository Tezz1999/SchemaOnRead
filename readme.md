# Schema-on-Read Data Analysis

## Overview

This Python project demonstrates a schema-on-read approach to data analysis, focusing on processing and analyzing sensor data stored in text files. The code is designed to execute specific queries on the dataset, resembling operations commonly performed in SQL databases, but through Python scripts. These operations include selecting data based on certain conditions, calculating averages, and analyzing subsets of the data for insights.

## Purpose

The purpose of this code is to showcase how unstructured or semi-structured data can be analyzed without a predefined schema. This approach is particularly useful for datasets that are too large or complex to be efficiently managed by traditional databases. By parsing and analyzing the data on-the-fly, we can gain insights and perform calculations such as averages and standard deviations directly from the raw data files.

## Queries

The project includes scripts for executing the following queries:

1. **Selecting Data**: Retrieves `pitime`, `temp_5`, and `temp_8` for entries within a specific time range.
2. **Calculating Average**: Computes the average of `temp_8` over a given time period.
3. **Analyzing CO2 Levels**: An additional query that selects a subset of data related to CO2 levels, calculating average, standard deviation, maximum, and minimum values.


# Results

The script prints the results of the queries to the console. For the first two queries, it will output a list of dictionaries with the selected data and the average temperature. For the additional query on CO2 levels, it will print the average, standard deviation, maximum, and minimum levels of CO2.
