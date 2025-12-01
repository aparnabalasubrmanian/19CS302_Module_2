# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE: 3.3.2025
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
```
1. Start  
2.Declare variables a, i, and fact = 1
3.Read input value and store it in a
4.For i = 1 to a (increment i by 1 each time)
5.Multiply fact by i and store result in fact
6.Print fact as the factorial value
7.Stop
```
## Program:
```
#include<stdio.h>
int factorial(int n);

int main()
{
    int num, fact;
    scanf("%d", &num);  
    fact = factorial(num); // function call 
    printf("Factorial value is: %d", fact);
    return 0;
}

int factorial(int n)
{
    int i, f = 1;
    
    for(i = 1; i <= n; i++){
        f = f * i;
    }
    
    return f; // returning result
}


```

## Output:
<img width="621" height="239" alt="image" src="https://github.com/user-attachments/assets/1803ffef-7ed5-4809-a3b4-a1b8d819243d" />




## Result:
Thus the program was executed and the output was verified successfully.
