# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.
### Step 2: 
 Using keyword "with" to open the requied file.
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.The four function is used to take each line from the main file.
### Step 6: 
The four function is used to take each line from the main file.
### Steo 7:
Print the output.
## PROGRAM:
```python
with open("git.txt","r") as f1:
    with open("MyFile.txt","a") as f2:
        for line in f1:
            f2.write(line)
```            

### OUTPUT:
![5c-1](https://user-images.githubusercontent.com/121608770/215401297-72a50451-0491-40d8-9b9b-69f4919469c2.jpg)
![5c3](https://user-images.githubusercontent.com/121608770/215402068-db33931f-70fd-486c-b369-4f99572e1d69.jpg)
![5c2](https://user-images.githubusercontent.com/121608770/215402075-9460c708-0ad4-4f7e-891c-b95a03c0f274.jpg)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
