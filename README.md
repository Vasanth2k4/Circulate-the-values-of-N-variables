# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a function to circulate the variables
### Step 2: 
Initialize a list from the user using eval
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
We do this initializing a variable 1 and adding the value before index and after the index in the list
### Step 6: 
print the value of 1
## Program:
```python
###Program to circulate N values.
###Developed by:VASANTHARAJ J
###RegisterNumber:23012935
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![image](https://github.com/Vasanth2k4/Circulate-the-values-of-N-variables/assets/147139769/ef7faf3a-1164-4f9c-9da7-8e2ed508d75a)
## Result:
The python program for Circulate-the-values-of-N-variables is execueted successful.
