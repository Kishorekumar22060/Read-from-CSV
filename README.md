# Exp6-Read-from-CSV

## AIM:

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
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:', len(f.axes[0]))
print('Col:', len(f.axes[1]))
```

## OUTPUT:
![280919055-68711323-f5f8-4a65-a33a-2773c6a6bcc4](https://github.com/Kishorekumar22060/Read-from-CSV/assets/141472136/7947cb19-5f54-4d40-a1e0-0c9b776bdfe6)


## RESULT:
Thus the program executed successfully.
