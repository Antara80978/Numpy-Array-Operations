# Task 12 - NumPy Array Operations

## AI & ML Internship - Veda Technology

### Objective
The objective of this task is to understand vectorized numerical operations using NumPy. Two NumPy arrays are created, and addition, subtraction, multiplication, and division operations are performed on them.

### Tools and Technologies
- Python
- NumPy
- Jupyter Notebook

### Project Description
This project demonstrates basic mathematical operations using NumPy arrays. Two numerical arrays are created, and arithmetic operations are performed directly on them without using loops.

### Code
```python
import numpy as np

# Create two NumPy arrays
arr1 = np.array([10, 20, 30, 40])
arr2 = np.array([2, 4, 5, 8])

# Display the arrays
print("First Array:", arr1)
print("Second Array:", arr2)

# Check the shape of both arrays
print("\nShape of First Array:", arr1.shape)
print("Shape of Second Array:", arr2.shape)

# Addition
addition = arr1 + arr2
print("\nAddition:", addition)

# Subtraction
subtraction = arr1 - arr2
print("Subtraction:", subtraction)

# Multiplication
multiplication = arr1 * arr2
print("Multiplication:", multiplication)

# Division
division = arr1 / arr2
print("Division:", division)
```

### Output
```text
First Array: [10 20 30 40]
Second Array: [2 4 5 8]

Shape of First Array: (4,)
Shape of Second Array: (4,)

Addition: [12 24 35 48]
Subtraction: [ 8 16 25 32]
Multiplication: [ 20  80 150 320]
Division: [5. 5. 6. 5.]
```

### Explanation of Operations

- **Addition:** Adds corresponding elements of both arrays.
- **Subtraction:** Subtracts corresponding elements of the second array from the first array.
- **Multiplication:** Multiplies corresponding elements of both arrays.
- **Division:** Divides each element of the first array by the corresponding element of the second array.

### What Is Vectorization?
Vectorization is the process of performing operations on entire arrays without explicitly writing loops. NumPy supports vectorized operations, making numerical computations concise and efficient.

### Why NumPy?
NumPy provides efficient numerical operations on arrays. It reduces the need for explicit loops and offers convenient mathematical functions for working with numerical data.

### Learning Outcomes
- Learned to create NumPy arrays using `np.array()`.
- Understood how to check the shape of arrays.
- Performed addition, subtraction, multiplication, and division on NumPy arrays.
- Understood the concept of vectorization.
- Learned how NumPy performs element-wise operations.

### Conclusion
This task helped me understand how NumPy performs mathematical operations on arrays. I learned how to create arrays, check their shapes, and perform basic arithmetic operations using vectorization.

### Author
Antara Sarvade

AI & ML Internship - Veda Technology
