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

![Screenshot_20230126_105110](https://user-images.githubusercontent.com/119560501/214907577-1621afb3-54a5-485d-878a-edc6813abd94.png)

### TEXT FILE:

![text file](https://user-images.githubusercontent.com/119560501/214907692-fee0ba6a-5fc8-4a5c-8ae4-6b49eda6f057.png)



## RESULT:
Thus the program is written to find the word count from a text.
