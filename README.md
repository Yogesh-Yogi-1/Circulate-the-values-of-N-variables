# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user.
### Step 2: 
Assign the value of second variable to a temporary variable.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the values it wuold be interchanged
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: V.Yogesh
#RegisterNumber:23013930
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
```

## OUTPUT
![Screenshot 2023-12-19 154022](https://github.com/Yogesh-Yogi-1/Circulate-the-values-of-N-variables/assets/148514598/675de1ca-7b1c-4563-97f5-ae3ed01b4287)


## RESULT:
Thus circulating n variables are successfully executed.
