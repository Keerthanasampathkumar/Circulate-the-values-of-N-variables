# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
### Step 6: 
## Program:
```
#Program to circulate N values.
#Developed by: Keerthana S
#RegisterNumber:22009006
a=eval(input())
b=int(input())
def circulate():
    for n in range(b+1):
        c=a[n:]+a[:n]
    return c
print("After circulating the values are:",circulate())    
```

## Output:

![record 2](https://user-images.githubusercontent.com/119477890/211263207-952cf774-3632-432a-8da1-38b82261a575.png)


## Result:
Thus the Circulate-the-values-of-N-variables are successfully executed
