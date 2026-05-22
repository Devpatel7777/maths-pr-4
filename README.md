# Statistical Distribution Analysis Using Python

## Overview

This project presents a comprehensive statistical analysis of transaction-based data using probability distributions and statistical transformation techniques. The objective is to understand transaction behavior, analyze distribution patterns, test data normality, and apply mathematical models for probability analysis.

The project demonstrates practical implementation of statistical concepts using Python and data visualization libraries.

---

# Objectives

* Analyze transaction behavior using probability distributions
* Test whether the dataset follows normal distribution
* Apply transformation techniques to stabilize variance
* Visualize probability density and cumulative probability
* Interpret transaction patterns using statistical methods

---

# Statistical Techniques Implemented

## Discrete Distributions

* Bernoulli Distribution
* Binomial Distribution
* Poisson Distribution

## Continuous Distributions

* Log-Normal Distribution
* Power Law Distribution

## Statistical Analysis

* Q-Q Plot
* Box-Cox Transformation
* Z-score Analysis
* Probability Density Function (PDF)
* Cumulative Distribution Function (CDF)

---

# Dataset Description

The dataset contains transaction-related information including:

| Feature            | Description                         |
| ------------------ | ----------------------------------- |
| Transaction Amount | Amount spent in each transaction    |
| Transaction Status | Success or Failed transaction       |
| Transaction Count  | Number of transactions per interval |

The dataset is used to study transaction distributions and customer behavior patterns.

---

# Technologies Used

| Technology  | Purpose                   |
| ----------- | ------------------------- |
| Python      | Programming Language      |
| Pandas      | Data Manipulation         |
| NumPy       | Numerical Computation     |
| Matplotlib  | Data Visualization        |
| Seaborn     | Statistical Visualization |
| SciPy       | Statistical Functions     |
| Statsmodels | Q-Q Plot Analysis         |

---

# Required Libraries

```python id="14w6pf"
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from scipy.stats import bernoulli
from scipy.stats import binom
from scipy.stats import poisson
from scipy.stats import lognorm
from scipy.stats import powerlaw
from scipy.stats import probplot
from scipy.stats import boxcox
from scipy.stats import zscore
from scipy.stats import norm
```

---

# Project Workflow

## 1. Data Loading and Preprocessing

* Loaded transaction dataset
* Checked missing values
* Performed statistical summary analysis

## 2. Bernoulli and Binomial Distribution

* Modeled transaction success and failure
* Calculated probability of successful transactions

## 3. Poisson Distribution

* Analyzed transaction occurrence frequency
* Modeled daily transaction counts

## 4. Log-Normal and Power Law Distribution

* Studied skewness in transaction amounts
* Identified heavy-tail transaction behavior

## 5. Q-Q Plot Analysis

* Tested normality of dataset
* Compared sample distribution with theoretical normal distribution

## 6. Box-Cox Transformation

* Reduced skewness
* Stabilized variance for improved analysis

## 7. Z-score Probability Analysis

* Detected unusual transaction values
* Computed probability of transactions exceeding ₹5000

## 8. PDF and CDF Visualization

* Visualized probability density distribution
* Analyzed cumulative transaction probability

---

# Key Findings

* Transaction amount data is positively skewed
* Transaction counts follow Poisson distribution
* Log transformation improves data normality
* Q-Q plot indicates non-normal distribution
* Box-Cox transformation stabilizes variance effectively
* Log-Normal distribution best fits transaction amount data
* Large transactions are rare but statistically significant

---

# Project Structure

```text id="h84q4g"
├── transaction_dataset.csv
├── Maths_project.ipynb
├── README.md
```

---

# Installation Guide

## Clone Repository

```bash id="a2pprm"
git clone <repository-link>
```

---

## Install Dependencies

```python id="6b5gfr"
pip install pandas numpy matplotlib seaborn scipy statsmodels
```

---

## Run Jupyter Notebook

```python id="7zyquj"
jupyter notebook
```

Open:

```text id="cx7a56"
Maths_project.ipynb
```

Run all notebook cells sequentially.

---

# Results and Interpretation

The analysis demonstrates how statistical distributions can be applied to real-world transaction data for probability estimation and behavioral analysis.

The project highlights:

* Distribution fitting
* Normality testing
* Probability estimation
* Variance stabilization
* Statistical visualization

These concepts are widely used in:

* Data Science
* Financial Analytics
* Machine Learning
* Risk Analysis
* Business Intelligence

---

# Conclusion

This project successfully applies statistical distribution analysis techniques to transaction data using Python. Through visualization and probability modeling, meaningful insights were extracted regarding transaction behavior and data distribution patterns.

The implementation provides a strong foundation in:

* Probability Theory
* Statistical Analysis
* Data Visualization
* Distribution Modeling

---

# Author

**Dev Patel**


