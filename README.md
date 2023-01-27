# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:import sys

### Step 2:Open file using open(). 
 
### Step 3:Use for loop.

### Step 4:Use len to count number of words.

### Step 5:Give print. 

### Step 6:End the Progran 

## PROGRAM:


```
# Developed by:keerthana jayasri s k
# Ref no : 22006582
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/121163440/215137771-09a781ca-c05e-4002-8668-7d05215b4649.png)
![image](https://user-images.githubusercontent.com/121163440/215137826-0b0c71ad-f189-4bb9-bece-a01ab9ee7c4e.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
