# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program
### Step 2: 
Get the input from the user using eval(input()) 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Using concentration operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: T.Ajay
#RegisterNumber:23007325
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)

```

### Output:
![image](https://github.com/Ajayreddy-2006/Circulate-the-values-of-N-variables/assets/145742508/5f80d651-9cb8-44cc-a044-2dcd8ad2b604)

## Result:
Thus the python program for circulate the values of n variable is exucuted successfully
