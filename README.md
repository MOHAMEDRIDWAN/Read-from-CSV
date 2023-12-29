# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
## Step 1:
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns.

## Step 5:
Print the output
## PROGRAM:
```
# Developed by: MOHAMED RIDWAN A
# Register Number: 23003133
import pandas as pd
df = pd.read_csv('nba (2).csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="790" alt="image" src="https://github.com/MOHAMEDRIDWAN/Read-from-CSV/assets/146993368/2b51f5b9-ba19-40d2-8e6d-ef24e014ebf5">

## RESULT:
Thus the program is written to copy the contents from one file to another file

