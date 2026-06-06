# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
import math
rows = int(input("Enter the number of rows for Pascal's Triangle: "))
for n in range(rows):
    print(" " * (rows - n), end="")
    for k in range(n + 1):
        # Formula: n! / (k! * (n-k)!)
        val = math.factorial(n) // (math.factorial(k) * math.factorial(n - k))
        print(val, end=" ")
    # Move to the next line after printing a row
    print()
```

## Sample Output
<img width="543" height="376" alt="image" src="https://github.com/user-attachments/assets/95486640-8b9f-479b-8174-128093850445" />


## Result

The Python program to generate Pascal's Triangle for a user-specified number of rows using combinatorial calculations and loop control structures was successfully written, executed, and verified.
