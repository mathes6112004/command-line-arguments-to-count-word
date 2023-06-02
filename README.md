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
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: MATHESWARAN K
RegisterNumber: 212222110024
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/mathes6112004/command-line-arguments-to-count-word/assets/119477782/b85e623c-a2a7-45c2-9a3d-0f7acf61de16)
![image](https://github.com/mathes6112004/command-line-arguments-to-count-word/assets/119477782/e9679634-758e-4b3d-9c73-1d90532242cb)
![image](https://github.com/mathes6112004/command-line-arguments-to-count-word/assets/119477782/75fb85b5-e1ac-4904-b3f2-d5b4c8df183f)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
