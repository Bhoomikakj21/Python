# Simple Linear Regression

Simple Linear Regression is a statistical method used to model the relationship between a **dependent variable (Y)** and a **single independent variable (X)** using a straight line:

\[
Y = mX + b
\]

where:  
- **Y** = dependent variable (target)  
- **X** = independent variable (feature)  
- **m** = slope of the line  
- **b** = intercept  

## Implementation in Python

### 1. Import Required Libraries
```python
import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
