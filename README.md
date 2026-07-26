# pga-histogram-cdf-analysis

Python project for statistical analysis and visualization of PGA data using histogram and CDF plots.

## Overview

This project analyzes a provided PGA dataset and computes the main statistical measures manually from their mathematical formulas rather than relying on NumPy built-in statistical functions.

The script:
- reads PGA values from `pga.txt`
- computes the number of data points
- computes the mean
- computes the range
- computes the sample standard deviation
- computes the skewness
- builds a histogram using manually defined bins
- identifies the PGA interval with the highest frequency
- computes and plots the cumulative distribution function (CDF)

## Files

- `pgaAnalysis.py` — main Python script for analysis and plotting
- `pga.txt` — input file containing PGA values

## Methods

The statistical values are calculated manually in the code using direct formulas:

- Mean
- Range
- Sample standard deviation
- Skewness
- Relative frequency
- Cumulative frequency / CDF

NumPy is only used to load the input data from the text file. The statistical calculations themselves are implemented manually.

## Output

The script prints the following results in the terminal:
- number of PGA values
- mean
- standard deviation
- range
- skewness
- interval with the highest frequency

It also generates:
- a histogram of PGA frequencies and proportions
- a CDF plot of PGA values

## How to Run

Make sure Python is installed, then install the required libraries if needed:
```bash
pip install numpy matplotlib
```

Run the script with:
python pgaAnalysis.py
