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

# Original array
arr = np.array([[5, 2, 9],
                [1, 6, 3],
                [8, 4, 7]])

# Column-wise sort
sorted_arr = np.sort(arr, axis=0)

print("Original Array:\n", arr)
print("Column-wise Sorted Array:\n", sorted_arr)
```

## Output
<img width="1912" height="765" alt="image" src="https://github.com/user-attachments/assets/f618c774-0878-45fa-9446-57467485d3a4" />


## Result
The program accepts a 2D NumPy array from the user, sorts each column in ascending order using np.sort(array, axis=0), and displays both the original array and the column-wise sorted array.
