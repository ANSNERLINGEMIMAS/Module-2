# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
x = int(input("Enter the first number: "))
y = int(input("Enter the second number: "))

f = lambda a, b: a + b
print("Sum:", f(x, y))
```

## Output
Enter the first number: 5  
Enter the second number: 7  
Sum: 12


## Result
The program successfully defines a lambda function to add two numbers and prints the result.
