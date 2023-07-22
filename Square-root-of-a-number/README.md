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
```
Program to find the square root for the given number(newton's method) using function.
Developed by: Harish R
RegisterNumber:  22005828
n1=int(input())
itr=100
def sqr(n1,itr):
    n2=float(n1)
    for i in range(itr):
        n1=0.5*(n1+n2/n1)
    print("Square root of the number: {}".format(n1))
sqr(n1,itr)
```

## Output:
![Screenshot (42)](https://user-images.githubusercontent.com/117935868/212720763-677cab46-82e2-4ddf-80cb-d4c3b731d111.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
