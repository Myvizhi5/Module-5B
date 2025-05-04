# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np

# Define two NumPy arrays
x = np.array([3, 5, 7, 9, 2])
y = np.array([1, 5, 6, 9, 3])

# Find indices where x >= y
indices = np.where(x >= y)

# Print the indices
print("Indices where x >= y:", indices[0])
```
## Output
```
Indices where x >= y: [0 1 2 3]
```
## Result
The program successfully finds the indices where the elements in array x are greater than or equal to the corresponding elements in array y and prints the indices where the condition is true.
