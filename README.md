# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Take the file name from the user.

### Step 2: 

The file is opened using the open() function in the read mode.

### Step 3: 

A for loop is used to read through each line in the file.

### Step 4:  

Each line is split into a list of words using split().

### Step 5: 

The number of words in each line is counted using len() and the count variable is incremented.

### Step 6: 

The number of words in the file is printed.

## PROGRAM:
```python 

Developed by : E. VARSHA SHARON
Register number : 22004867


fname=input('Enter file name: ')
num_words = 0
with open(fname, 'r') as f :
    for line in f:
        words=line.split()
        num_words += len(words)
print('Number of words: ',num_words)
```
### OUTPUT:
[!OUTPUT]![wcnt](https://user-images.githubusercontent.com/98278161/214894127-9fc3a64d-cf88-4542-953a-bc58adaa7ed7.jpeg)


## RESULT:
Thus the program is written to find the word count from a text.
