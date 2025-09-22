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
# Developed by:sanjay kumar B
# Register no:212224230242
def circulate():
   
    arr = eval(input())   
    n = int(input())      
    
    
    n = n % len(arr) 
    result = arr[n:] + arr[:n]
    
    print("After circulating the values are:", result)
```
## Output:
<img width="1353" height="401" alt="image" src="https://github.com/user-attachments/assets/b7eec5b3-982f-478d-a0d9-08b962a16938" />


## Result:
executed
