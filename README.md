# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
~~~
Developed By:Ranjith D
Register no.:21500662
~~~
~~~
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(10))
print("Colunm",len(df.axes[0]))
print("Row",len(df.axes[1]))
~~~
## OUTPUT:
![output](https://github.com/RanjithD18/Read-from-CSV/blob/main/Screenshot%20(1).png)
## RESULT:
