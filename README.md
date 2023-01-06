# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Assume the keyword to run the program
### Step 2: 
use the circulate command
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
assign the second value
### Step 6: 
print the value of the first variable
```
## Program:
#Program to circulate N values.
#Developed by: mourise jane
#RegisterNumber:22009459
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![output](./Screenshot%20(9).png)


## Result:
Executed succsessfully