# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.
### Step 2: 
Give a new file name to create a copy of a file content. 
### Step 3: 
Read the file and close the file.
### Step 4:  
Now write the content in the new file.
### Step 5: 
When done print"File copied successfully".
### Step 6: 
End of the program
## PROGRAM:
```
# To write a program for coping the contents from one to another file.
# Developed by : prem kumar g
#RegisterNumber:23003614
with open("file1.txt","r") as f:
    x=f.read()
with open("file2.txt","w") as f1:
    f1.write(x)
```
### OUTPUT:

![image](https://github.com/PremkumarG3/copy-file/assets/138955646/663aee29-2b67-4c4f-864e-792f69fe4e4b)


![Screenshot 2023-12-31 171116](https://github.com/PremkumarG3/copy-file/assets/138955646/f3478bdb-42e0-4884-8ceb-0120978fb561)


![Screenshot 2023-12-31 171149](https://github.com/PremkumarG3/copy-file/assets/138955646/0a83db7e-f394-4e26-8ebc-e1d1e727d583)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
