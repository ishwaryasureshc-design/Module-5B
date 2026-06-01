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

x = np.array([5, 2, 7, 4])
y = np.array([3, 2, 6, 8])

print("x > y:", x > y)
print("x == y:", x == y)

indices = np.where(x >= y)
print("Indices where x >= y:", indices)

```

## Output
<img width="1363" height="703" alt="Screenshot 2026-06-01 114508" src="https://github.com/user-attachments/assets/acdaea69-65a3-4416-9df8-77e353884a4d" />

## Result
The program compares two NumPy arrays x and y, finds the positions where the elements of x are greater than or equal to the corresponding elements of y using np.where(x >= y), and prints those indices.
