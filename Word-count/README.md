# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function "with".



### Step 2: 
 Then assign the i value in the file.


### Step 3: 
Use split function to spilt the words


### Step 4:  
Find the given length of the words by using len() fuction.


### Step 5: 
Call the function and Printing the number of words.


### Step 6: 
End the program

## PROGRAM:
```
Python program for getting the word count from a text file
Developed by: Harish R
Ref no: 22005828

num_word=0
with open ("textfile.txt",'r') as f:
    for i in f:
        word=i.split()
        num_word+=len(word)
print("number of words ={}".format(num_word))
```

### OUTPUT:
![image](https://user-images.githubusercontent.com/117935868/214642143-bc32f30e-7533-4e00-a181-f6f7140a7a5f.png)


![image](https://user-images.githubusercontent.com/117935868/214642180-38a9a8c2-bff3-489a-9f26-0f9377734f8f.png)



## RESULT:
Thus the program is written to find the word count from a text.
