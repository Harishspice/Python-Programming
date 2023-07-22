# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Developed by: Harish R
RegisterNumber: 22005828
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: Harish R
RegisterNumber: 22005828
def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: Harish R
RegisterNumber: 22005828
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark


```
## Sample Input and Output
![image](https://github.com/Harishspice/Python-Programming/assets/117935868/4a5a8f59-3dd9-4bbd-bdd1-0197e17720dd)

## Output:

# To find the maximum of marks using the list method sorts.
![Screenshot (49)](https://user-images.githubusercontent.com/117935868/214078818-a7ae2239-449b-4073-9625-6c045989bf1d.png)

# To find the maximum marks using the list method max().
![Screenshot (50)](https://user-images.githubusercontent.com/117935868/214077640-c8f3a29f-9f45-4140-9b23-7e39adc3d591.png)

# To find the maximum marks without using builtin functions
![Screenshot (51)](https://user-images.githubusercontent.com/117935868/214077869-64ae12f7-5f20-487c-b44e-3bc396d84ed5.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
