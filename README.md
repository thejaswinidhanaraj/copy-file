# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program

### Step 2:

 Open the file f1 in read mode
 
### Step 3: 
Open the file f2 in write mode

### Step 4:  
Copy the contents using write() with the for loop

### Step 5: 
End the program

## PROGRAM:
```
#Python program for copying the content from one file to another file
#Developed by: THEJASWINI 
#Reference Number : 212223110059
def copy(fname,newfile):
    with open(fname,'r')as fp:
        with open(newfile,'w')as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")   
newfile("Enter a name for nrw file: ")
copy(fname,newfile)
```
### OUTPUT:



## RESULT:
Thus the program is written to copy the contents from one file to another file.
