# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we want to create a text file.
### Step 2: 
Then we want to create a python file. 
### Step 3: 
In that python file we want to write apython code to display
a word count.
### Step 4:  
We want to use commant with Open in that type that saved text file.
### Step 5: 
Then write a revelant program.

## PROGRAM:
### To write a python program for getting the word count from the contents of a file using command line arguments.
```python
#Developed by : YUVARAJ.S
#Register Number : 22008589
import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```
### OUTPUT:
![output](./5b%201.jpeg)
![output](./5a%202.jpeg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
