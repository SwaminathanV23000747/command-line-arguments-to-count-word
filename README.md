# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Prompt for file name: Get the name of the file to count words in.
### Step 2: 
Initialize word count: Set a counter variable to 0.
### Step 3: 
Open and process file: Open the specified file in read mode, iterate through each line, split it into words, and add the 
word count for each line to the total count.
### Step 4:  
Close file: Ensure the file is properly closed.
### Step 5: 
Print result: Display the total number of words found in the file.
## PROGRAM:
```python
#Program to find the Word Count using command line arguments
#Developed by : Swaminathan V
#Register umber : 23000747
fname=input("Enter the file name:")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len (words)
print('Number of words: ',num_words)
```
### OUTPUT:
![Screenshot 2024-01-01 145924](https://github.com/SwaminathanV23000747/command-line-arguments-to-count-word/assets/148931113/47124bc8-7b2c-4beb-90eb-bddce67be969)
![Screenshot 2024-01-01 145120](https://github.com/SwaminathanV23000747/command-line-arguments-to-count-word/assets/148931113/f4a3aa49-0707-4332-87a5-22f2d38eab55)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
