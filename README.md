# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:Create a text1.txt with some content in it
## Step 2: Open the text1.txt file in read mode
## Step 3:Create a copy.txt file using write mode
## Step 4: Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Programmed By: S.Shashin prasad
RegisterNumber: 212222230144
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![WhatsApp Image 2023-06-14 at 14 39 10](https://github.com/shashinprasad/copy-file/assets/129143499/f8e027ea-f1a9-4701-8bf0-cbdd857d8d19)
![WhatsApp Image 2023-06-14 at 14 39 10](https://github.com/shashinprasad/copy-file/assets/129143499/8de50e99-a460-47c6-b252-903e5486b472)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
