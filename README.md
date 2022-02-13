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
assign a variable count=0 
### Step 3: 
open a file in read mode
### Step 4:  
iterate a variable(lines)through the file
### Step 5: 
assign a variable word = line.split()
### Step 6: 
iterate through the variable and increase the count:and print the count vaalues
## PROGRAM:
#Developed By:-k.Sucharitha
#Reference number:-21003377
import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)

### OUTPUT:
![ju1](https://user-images.githubusercontent.com/94166007/153749755-91ff9d82-85d4-4fa6-ba71-d42771610a46.PNG)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
