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
def pascal(n):
    triangle=[]
    for i in range(n):
        k=[1]*(i+1)
        for j in range(1,i):
            k[j]=triangle[i-1][j-1]+triangle[i-1][j]
        triangle.append(k)
    for row in triangle:
            print(" ".join(map(str,row)))
n=int(input())
pascal(n)
```

## Sample Output
![Screenshot 2025-05-13 181814](https://github.com/user-attachments/assets/4eacc710-29b4-4d9b-bbc3-113b8c54688f)



## Result
The program successfully generates Pascal’s Triangle based on the number of rows entered by the user.

