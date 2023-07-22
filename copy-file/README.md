# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file from one file to another file.


### Step 2: 
 Using key word "with" to open the required file.


### Step 3: 
Again using the with keyword to open the empty file.


### Step 4:  
The empty file is open by using "w" which is used to write only.


### Step 5: 
The for fuction is used to take the each linefrom the main file.


### Step 6: 
End the program

## PROGRAM:
```
Developed By:  Harish R, 
Ref No: 22005828 

with open("file1.txt","r") as fp:
    with open("file2.txt",""w") as fp1:
        v = fp.read()
        fp1.write(v)
```

### OUTPUT:

![image](https://user-images.githubusercontent.com/117935868/214647725-0b21cb28-b231-4ebb-9343-a894214a6958.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
