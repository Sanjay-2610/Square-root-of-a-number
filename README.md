# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```py
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: Sanjay Ragavendar M K 
RegisterNumber: 22009286
*/
def sqroot(b,iter=100):
    a=float(b)
    for i in range(iter):
        b = 0.5*(b+a/b)
    return b
b=int(input())
print('Square root of the number:',sqroot(b))
```

## Output:
![image](https://user-images.githubusercontent.com/91368803/214847764-7522c925-3dda-4ce9-9dbb-a2e3d9e4f4ff.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
