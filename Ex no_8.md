# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE: 3.3.2025
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm:
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Enter number for multiplication and division. 
6. End.    

## Program:
```
#include<stdio.h>
void multiply();
void divide();

int main()
{
    multiply(); 
    divide();   
    
    return 0;
}

void multiply()
{
    float a, b, mul;
    scanf("%f %f", &a, &b);
    
    mul = a * b;
    printf("Multiplication is: %.2f\n", mul);
}

void divide()
{
    float a, b, div;
    scanf("%f %f", &a, &b);
    
    if(b == 0){
        printf("Division not possible (Denominator is 0)\n");
    } else {
        div = a / b;
        printf("Division is: %.2f", div);
    }
}

```

## Output:
<img width="595" height="301" alt="image" src="https://github.com/user-attachments/assets/2a4064b6-b457-40e2-ac3e-ceabbe951f2a" />



## Result:
Thus the program was executed and the output was verified successfully.
