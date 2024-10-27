# Ex-2 : Circulate-the-values-of-N-variables
## Date:
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
# Developed by: Jude Clement Jose
# Register no: 24005310
def circulate():
    list1=eval(input())
    count=int(input())
    for i in range (count):
        list1.append(list1[0])
        list1.pop(0)
    print("After circulating the values are:",list1)
    return
```

## Output:
![Screenshot 2024-10-27 112009](https://github.com/user-attachments/assets/b925a8b6-dbd1-4982-81c3-653ea3287508)


## Result:
The output for circulate the values of n variables is successfull.
