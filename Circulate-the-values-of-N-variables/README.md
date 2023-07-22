# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 

### Step 1: 
Declare a function for the program

### Step 2: 
Get the value from the user for the variables to be rotated

### Step 3: 
Get the value from the user for the number of rotation

### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Now, print the values

### Step 6: 
End the program 

## Program:
```
#Program to circulate N values.
#Developed by : Harish R 
#RegisterNumber:22005828
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![image](https://github.com/Harishspice/Python-Programming/assets/117935868/645b286f-870d-4283-bf13-fc1d1b71f99a)

## Result:
Thus, circulating of n variables using functions is successfully executed
