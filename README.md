# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0

### Step 2:
open it with txt file
 
### Step 3: 
Give range for i

### Step 4:
Then next split the words

### Step 5: 
count the number of words

### Step 6: 
Giving print statement for getting output

## PROGRAM:
```
num_words =0
with open('thala','r') as file1:
 for i in file1:
   word =i.split()
   num_words += len(word)
print("Number of words={}".format(num_words))
```

### OUTPUT:
![Screenshot 2023-12-23 105416](https://github.com/syedfayaz3105/Word-count/assets/147144126/e5e2afe1-7de7-4867-82b6-597bbe614ee4)




## RESULT:
Thus the program is written to find the word count from a text.
