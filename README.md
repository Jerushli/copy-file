# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
```
Step 1:
Create a text1.txt with some content in it

Step 2:
Open the text1.txt file in read mode

Step 3:
Create a copy.txt file using write mode

Step 4:
Copy the content of text1.txt file to copy.txt using write function

```

## PROGRAM:
```
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:


![image](https://github.com/Jerushli/copy-file/assets/120041243/02ec1170-32b1-4f2d-9aa1-60e8f1bdf1ff)



![image](https://github.com/Jerushli/copy-file/assets/120041243/35e58540-354b-43ac-9d95-8314949a5c64)




![image](https://github.com/Jerushli/copy-file/assets/120041243/f9e126e3-6df2-4ebf-9ae5-a8092cf75216)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
