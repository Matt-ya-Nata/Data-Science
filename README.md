# 📊 NumPy Arrays – Python Notebook

**NumPy**, the powerful numerical computing library in Python. This notebook demonstrates how to work with arrays, both 1D (vectors) and 2D (matrices), and showcases key operations like indexing, random number generation, and inspecting array metadata.

---

## 🔍 Overview

This project covers:

- Creating 1D and 2D NumPy arrays
- Random number generation
- Indexing and slicing arrays
- Finding maximum values
- Checking array shape and data type

---

## 📘 Code Examples

### 🎲 Creating a Random Integer Array

```python
from numpy.random import randint

ranarr = randint(1, 50, 10)
print(ranarr)
# Example Output: array([22,  6, 18,  3, 10, 10, 16, 40, 22, 35])
```

### 🏆 Finding the Index of the Maximum Value

```python
ranarr.argmax()
# Output: 7 (index of the maximum value)
```

### ➕ Creating a Simple 1D Array and Inspecting It
```
import numpy as np

arr = np.arange(25)
print(arr)
# Output: array([ 0,  1,  2, ..., 24])

print(arr.shape)
# Output: (25,)

print(arr.dtype)
# Output: dtype('int32')
```

### 🎯 Generating a Random Integer Between 2 and 10

```python
randint(2, 10)
# Output: 8 (example)
```

### 🔢 NumPy Indexing and Selection
```python
arr_new = np.array([1, 2, 3, 4, 5, 6])
arr_new[arr_new < 3]
# Output: array([1, 2])
```
### 🧮 Condition-Based Filtering
```python
arr_new = np.array([1, 2, 3, 4, 5, 6])
arr_new[arr_new < 3]
# Output: array([1, 2])
```
### 🧩 Working with 2D Arrays
```python
arr_2d1 = np.arange(50).reshape(5, 10)
print(arr_2d1)
# Output:
# [[ 0,  1,  2,  3,  4,  5,  6,  7,  8,  9],
#  [10, 11, 12, 13, 14, 15, 16, 17, 18, 19],
#  [20, 21, 22, 23, 24, 25, 26, 27, 28, 29],
#  [30, 31, 32, 33, 34, 35, 36, 37, 38, 39],
#  [40, 41, 42, 43, 44, 45, 46, 47, 48, 49]]

# Slicing a submatrix from rows 3 to 4 and columns 1 to 2
arr_2d1[3:5, 1:3]
# Output:
# [[31, 32],
#  [41, 42]]
```
### 📌 Key Notes
- Vectors = 1D arrays
- Matrices = 2D arrays
- randint() generates random integers
- .argmax() returns the index of the highest value
- .shape shows the array’s dimensions
- .dtype tells the data type of the array elements
- Boolean indexing helps filter arrays efficiently


### ✅ Requirements
- Python 3.x
- NumPy
  
### 🔧 Install NumPy:

``` bash
pip install numpy
```

