---
title: "Data Analysis with Python"
# excerpt: "Short description of portfolio item number 1<br/><img src='/converter_3dview.png'>"
collection: portfolio
---
In this project, I utilised Python programming to analyze a provided dataset, applying various statistical and data visualization techniques.

## Libraries 

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split, cross_val_score
from sklearn.metrics import r2_score, mean_squared_error
from sklearn.preprocessing import PolynomialFeatures, StandardScaler
```


## Original Data Set Analysis

- Dataset loading
- Dataset statistical analysis: printing number of samples, calculating  Q1 and Q3 quantiles, Inter Quantile Range (IQR), outliers.
- Data visualisation with plots, subplots, boxplots etc.

## Data Preprocessing

- defining functions to handle invalid values, outliers, missing values, handling NaN and handling duplicates.

## Data visualisation 
- Histograms
- correlation matrix
- Heatmaps

## Probability Analysis
- Threshold-based probability estimation
- Cross tabulation 
- Conditional probability 

## Statistical Theory Applications
- Law of Large Numbers
- Central Limit Theorem