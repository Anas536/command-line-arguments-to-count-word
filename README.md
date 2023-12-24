# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

import sys

### Step 2:

Then decleare count is equal to 0
 
### Step 3: 

read the file with python file name

### Step 4:  

Splitting the word

### Step 5: 

After splitting count the number of words in the line

### Step 6: 

In last statement give the print statement.

## PROGRAM:
```
Developed by : Mohamed Anas O.I
Register no : 23008005
import sys
count=0
with open(sys.argv[1],'r) as f:
    for line in f:
    word=line.split()
    count+=line.(word)
print("Word Count in File=",count)
```

### OUTPUT:

![Screenshot 2023-12-24 204624](https://github.com/Anas536/command-line-arguments-to-count-word/assets/139841834/dec35555-9045-4fbd-b4b9-fa6618783ef0)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
