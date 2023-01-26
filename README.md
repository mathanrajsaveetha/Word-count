# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code or jupyter lab.

### Step 2:
Create file with .py extension.

### Step 3:
Also create .txt file and input sentences.

### Step 4:
Write the code.

### Step 5:
Run the program.

### Step 6:
Print the values and end the program.
```
## PROGRAM:
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : MATHAN RAJ E
## REFERENCE NO : 22008971
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/119560501/214905044-e25cd6fa-21a7-45a5-94b2-88b88afea177.png)

### TEXT FILE:
![Screenshot_20230126_105110](https://user-images.githubusercontent.com/119560501/214907070-0315fbd6-3835-4df0-9508-7ee8d0260cbb.png)



## RESULT:
Thus the program is written to find the word count from a text.
