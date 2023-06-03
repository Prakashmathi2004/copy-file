# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: PRAKASH M
RegisterNumber: 212222100035
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![5c](https://github.com/Prakashmathi2004/copy-file/assets/118350045/3433660f-5528-49cd-893b-e51c52325642)

![5c1](https://github.com/Prakashmathi2004/copy-file/assets/118350045/c50cbfac-8082-4450-94cd-940dc4b2fcb3)

![5c2](https://github.com/Prakashmathi2004/copy-file/assets/118350045/d20397d8-b77b-425f-9e5e-6fc50fdcf246)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
