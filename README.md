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
Give two examples
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
End the program 
## Program:
~~~
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~
## Output:
![image](https://github.com/Sheetalshee/Circulate-the-values-of-N-variables/assets/144979107/280ccc6f-9618-452c-a41d-1eedb422e819)


## Result:The program is excuted successfully.
