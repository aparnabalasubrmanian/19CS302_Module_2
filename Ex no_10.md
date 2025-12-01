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
int main()
{
    int a,i,fact=1;
    scanf("%d",&a);
    for(i=1;i<=a;i++){
        fact=fact*i;
    }
    printf("Factorial value is: %d",fact);
    
    return 0;
}

```

## Output:
<img width="1204" height="406" alt="image" src="https://github.com/user-attachments/assets/05771cfd-6b9f-41fa-aa4e-7b5018a228ba" />



## Result:
Thus the program was executed and the output was verified successfully.
