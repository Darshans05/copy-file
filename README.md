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
```python 
''' 
Program for copying the contents from one file to another file
Developed by: DARSHAN S
RegisterNumber: 212222100010
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![image](https://github.com/Darshans05/copy-file/assets/115534676/5bf4d1fe-20b9-4de7-8112-56906bfcd6c9)
![image](https://github.com/Darshans05/copy-file/assets/115534676/04f71081-3a7a-4b9a-8ba8-963bf12e5a41)
![image](https://github.com/Darshans05/copy-file/assets/115534676/7d6c2631-bc40-4a40-9e1d-a27eb01fdeca)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
