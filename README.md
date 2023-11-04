# Read-from-CSV

## AIM:
To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1: 
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.

### Step 3:
 Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: SWETHA.S
#RegisterNumber: 212222230155
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:

![image](https://github.com/swethaselvarajm/Read-from-CSV/assets/119525603/7abcc311-6159-4afa-8b99-e133b1906769)

## RESULT:
Hence the python programe to read the contents from a csv file is executed successfully.
