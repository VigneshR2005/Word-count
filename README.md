# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
Hardware:PC

Software:Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a new text file and add comment

### Step 2: 
create a python file and add program
### Step 3: 
Run the program 
### Step 4:  
Get the output 
### Step 5: 
Take the output as screenshot
### Step 6: 
End of the program.
## PROGRAM:
``` 
fname=input("Enter file name:")
num_words=0
with open(fname,'r')as f:
    for line in f:
        word=line.split()
        num_words+= len(words)
    print("Number of words:",num_words)
```
### OUTPUT:
![](/Word%20count.png)


## RESULT:
Thus the program is written to find the word count from a text.
