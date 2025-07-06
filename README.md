# NumPy Arrays - Python Notebook

This Jupyter Notebook explores the basics of NumPy arrays, including one-dimensional (vectors) and two-dimensional (matrices) arrays. It also demonstrates basic operations such as random number generation, array shape inspection, and data type checking.

## 🔍 Overview

The notebook covers:

- Creating 1D and 2D NumPy arrays
- Generating random arrays
- Finding the index of the maximum value
- Inspecting array shape and data type

## 📘 Example Snippets

### Creating a Random Integer Array

```python
from numpy.random import randint

ranarr = randint(1, 50, 10)
print(ranarr)
# Example Output: array([22,  6, 18,  3, 10, 10, 16, 40, 22, 35])
```
### Finding the Index of the Maximum Value

```python
ranarr.argmax()
# Output: 7 (index of the maximum value)
```
### Creating a Simple 1D Array and Inspecting It
```python
import numpy as np

arr = np.arange(25)
print(arr)
# Output: array([ 0,  1,  2, ..., 24])

print(arr.shape)
# Output: (25,)

print(arr.dtype)
# Output: dtype('int32')
```
### Generating a Random Integer Between 2 and 10

```python
randint(2, 10)
# Output: 8 (example)

```
## 📌 Notes

- Vectors: 1-dimensional arrays.
- Matrices: 2-dimensional arrays.
- NumPy's randint() is used for random integer generation.
- .argmax() returns the index of the maximum value in the array.
- .shape returns the structure of the array.
- .dtype reveals the data type of array elements.

### ✅ Requirements
- Python 3.x
- NumPy
## Install NumPy with:

```bash
pip install numpy
```

  




