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
#Developed by; M Sanjay
#Register Number: 212222240090

def sq(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5*(number+a/number)
    return number
a=int(input())
print("Square root of the number:",sq(a))
```

## Output:
![Screenshot 2023-06-07 092851](https://github.com/Sanjay22006832/GCD-of-two-numbers/assets/119830477/73d836c0-5db4-4e5c-a7bb-abcd47dd13fe)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
