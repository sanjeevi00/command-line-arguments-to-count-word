# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words

## PROGRAM:
```python
"""
Developed by:Sanjeevi J
RegisterNumber: 212222110040
"""
import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:
![image](https://github.com/sanjeevi00/command-line-arguments-to-count-word/assets/121484976/3886a6a5-6f39-413c-a3af-f88abe645463)

![image](https://github.com/sanjeevi00/command-line-arguments-to-count-word/assets/121484976/9f7c0311-98af-49e7-bda7-b806a383354a)

![image](https://github.com/sanjeevi00/command-line-arguments-to-count-word/assets/121484976/5f3d572c-e558-4930-89a9-99d4653e9330)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
