# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that sile. 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
Developed by: DIVYA E
Register number:212223230050

def copy(filename,newfile):
    with open(filename,'r') as fp:
       with open(newfile,'w') as fp1:
          data1=fp.read()
          fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
```
### OUTPUT:
![Alt text](5c-1.png)
![Alt text](5c-2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.