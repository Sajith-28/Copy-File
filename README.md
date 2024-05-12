# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Get the file name and location from the user.

## Step 2:
Give a new file name to create a copy of a file content.

## Step 3:
Read the file and close the file.

## Step 4:
Now write the content in the new file.

## Step 5:
When done print "File copied sucessfully"

## Step 6:
End of the program.

## PROGRAM:
```Python
Developed by: SAJITH AHAMED F
Reg No: 212223240144
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![alt text](<exp 11.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
