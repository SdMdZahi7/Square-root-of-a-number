# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
#Developed by: Syed Muhammed Zahi 
#RegisterNumber: 21004029  
*/
def square(x,num_iters=100):
    b=float(x)
    for i in range(num_iters):
        x=0.5*(x+b/x)
    return(x)
b=int(input())
print("Square root of the number:",square(b))
        
```

## Output:
![zsquareout](https://user-images.githubusercontent.com/94187572/147853727-4f4e1bf1-c6eb-4240-a2d4-d7b1543cf562.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
