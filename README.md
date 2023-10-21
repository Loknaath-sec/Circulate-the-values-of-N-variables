# Circulate-the-values-of-N-variables

## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last, print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by: P.LOKNAATH
#RegisterNumber: 23004546

def circulate():
    l=eval(input())
    n=int(input())
    out=l[n:]+l[:n]
    print(f"After circulating the values are: {out}")
```
## Output:
![Exp 1b Output](https://github.com/Loknaath-sec/Circulate-the-values-of-N-variables/assets/145742558/793b88ee-d3c6-46c3-a2ef-bc072bf2955e)

## Result:
Thus the python program to circulate the n variables using function concept is successfully executed.




