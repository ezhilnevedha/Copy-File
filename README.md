# Copy-File
### NAME: EZHIL NEVEDHA.K
### REGISTER NUMBER:212223230055
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import pandas as pd
### Step 2: 
 Read the csv file using read_csv method
### Step 3: 
Use head and tail method to get the required contents from the file.
### Step 4:  
Use len() method to get the number of rows and columns.
### Step 5: 
End of the program.

## PROGRAM:
```
print("Enter the name of source file:")
sFile=input()
print("Enter the name of target file:")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()

fileHandle=open(tFile,"w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")

```
### OUTPUT:
![alt text](<Screenshot 2024-05-11 215401.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
