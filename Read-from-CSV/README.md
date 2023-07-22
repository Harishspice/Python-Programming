# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.



## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.


### Step 2:
Print the number of contents to be displayed using df.head().


### Step 3:
The number of rows returned is defined in Pandas option settings.


### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement and increase the maximum number of rows to display the entire DataFrame.


### Step 5:
End the program

## PROGRAM:
```
Developed by: Harish R
REGISTER NUMBER: 22005828

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/117935868/214648972-478476e1-fbca-42f8-b747-b27cdb38ca94.png)


## RESULT:
Thus the program is written to read the csv file.
