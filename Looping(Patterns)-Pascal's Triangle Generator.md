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
from math import comb

def pascal_triangle(n):
    for i in range(n):
        row=[]
        for j in range(i+1):
            row.append(str(comb(i,j)))
        print(" ".join(row))
        
n=int(input())
pascal_triangle(n)
```


## Sample Output
<img width="545" height="251" alt="Screenshot 2025-10-21 093229" src="https://github.com/user-attachments/assets/965e7645-0182-4371-af5c-97a5ea806075" />


## Result
Thus,the Python program that generates **Pascal's Triangle** is Executed successfully.


