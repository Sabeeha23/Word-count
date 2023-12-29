# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in text mode.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator. We assume that wwords in a sentence are separated by a space character.
### Step 4:  
The length of the split list should be equal to the number of words in a text file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
#Developed by: Sabeeha Shaik
#Register Number: 23012003
```
num_words = 0
with open("Untitled.ipynb",'r') as file1:
    for i in file1:
        word = i.split()
    num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![Screenshot 2023-12-29 205134](https://github.com/Sabeeha23/Word-count/assets/150231876/3abc81f8-2f47-482e-9a29-e6ed261a0680)



## RESULT:
Thus the program is written to find the word count from a text.
