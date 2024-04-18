# Time Series Analysis Example

## Overview

This project demonstrates basic time series analysis using a dataset containing greenhouse data. The Python libraries `pandas`, `numpy`, and `datetime` are used to manipulate and prepare the data for analysis.

[Watch the Video!](https://www.youtube.com/watch?v=ks1QDtWrG_4&t=1s)

## Files

- `greenhouse.csv`: CSV file containing time series data of greenhouse conditions.

## Requirements

- Python 3
- pandas
- numpy
- datetime

## Setup and Installation

1. Ensure Python 3 and pip are installed.
2. Install required packages:

```bash
pip install pandas numpy
```

3. Clone this repository and navigate into the project directory.

## Usage

Run the Jupyter notebook or Python script provided:

```bash
python timeseries_analysis.py
```

## Description of Data

The dataset includes the following columns:

- `id`: Identifier for the data entry.
- `modified`: Timestamp of the data entry.
- Various environmental measurements such as temperature, humidity, etc.

## Example Operations

1. **Data Loading**: Data is loaded from `greenhouse.csv`.
2. **Basic Analysis**: Includes checking column names, viewing data types, and initial data exploration.
3. **Grouping and Aggregation**: Data is grouped by `date_time` and averages are calculated for different intervals.

This project serves as a simple introduction to handling and analyzing time series data in Python.