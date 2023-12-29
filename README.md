# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mode.
### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentence are separated by a space character.
### Step 4:  
The length of the split list should be equal to the number of words in the text file.
### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
#word count from a text
#Developed by: Sabeeha Shaik
#Register number: 23012003
num_words = 0
with open("Untitled.ipynb",'r') as file1:
    for i in file1:
        word = i.split()
    num_words += len(word)
print("Number of words={}".format(num_words))

### OUTPUT:
![Screenshot 2023-12-29 205134](https://github.com/AkilaMohan/Word-count/assets/150231876/926f4b12-bf08-45b0-922e-90fb15c6a13c)

## RESULT:
Thus the program is written to find the word count from a text.
