# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
Import the sys module.

### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3: 
Read the file using read() method.

### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.

### Step 6: 

Run the program to determine the number of words in the file created.

## PROGRAM:

```
#To find the word count using command line arguments
#Developed by : Rajalakshmi R
#Reg no : 212223110037

fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))

```


### OUTPUT:
![image](https://github.com/Raji1009/command-line-arguments-to-count-word/assets/89059861/02fbc40d-496f-4ee1-802c-4b6b62b80e6b)

![image](https://github.com/Raji1009/command-line-arguments-to-count-word/assets/89059861/4372428e-ec81-418d-90c6-f54b026f9d39)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
