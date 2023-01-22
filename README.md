# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:

Get the value form the user for rotation.

### Step 2:

Get the value from the user for the number of rotation

### Step 3: 

Using the slicing concept rotate the list

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

![Screenshot 2023-01-22 094524](https://user-images.githubusercontent.com/119477890/213900316-18c08233-1c4b-4db5-b30d-a97cbd294865.png)




## Result:

Thus the program is developed for circulate the n variables.
