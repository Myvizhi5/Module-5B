# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

# Example: define a 2D NumPy array
arr = np.array([[3, 1, 5], [4, 7, 2], [9, 6, 8]])

# Sort the array column-wise (ascending order)
sorted_arr = np.sort(arr, axis=0)

# Display original and sorted arrays
print("Original Array:")
print(arr)
print("\nColumn-wise Sorted Array:")
print(sorted_arr)
```

## Output
```
Original Array:
[[3 1 5]
 [4 7 2]
 [9 6 8]]

Column-wise Sorted Array:
[[3 1 2]
 [4 6 5]
 [9 7 8]]
```

## Result
The program successfully sorts the elements in each column of a 2D NumPy array in ascending order and displays both the original and the sorted arrays.
