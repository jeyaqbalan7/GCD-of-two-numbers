# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: Jeyabalan
RegisterNumber: 212222240040 
*/
def gcd():
    n,m=int(input()),int(input())
    if n>m:
        min=n
    else:
        min=m
    for i in range(1,min+1):
        if n%i==0 and m%i==0:
             gcd=i
    print('GCD of two numbers is:',gcd)
```

## Output:
![gcd of two number](gcd.png)
![image](https://github.com/jeyaqbalan7/GCD-of-two-numbers/assets/119393851/0be77135-8d0f-4a3c-8869-1a33028b0cb7)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
