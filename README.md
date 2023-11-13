# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"

###Step 2:
Using split function to split the words.

### Step 3:
Finding the length of the words by using len() function.

### Step 4:
Calling the function and printing the number of words.

## PROGRAM:
```
Developed By: DEEPAK RAJ S
Register No: 212222240023

n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)
```
### INPUT:
![image](https://github.com/DEEPAK2200233/Word-count/assets/118707676/b7cc4bb2-ebd4-4b8d-99e9-5e67e20b0a5c)

### OUTPUT:
![image](https://github.com/DEEPAK2200233/Word-count/assets/118707676/ff3d19d1-19c5-4fef-b305-87be8ed2abe5)

## RESULT:
Thus the program is written to find the word count from a text.
