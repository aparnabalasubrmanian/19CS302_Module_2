# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
```
1.Start the program.
2.Take input of a number num and initialize sum to 0.
3.Use a do-while loop to extract each digit of num.
4.Check if the digit is odd; if yes, add it to sum.
5.Print the sum and end the program. 
```
## Program:
```
/*
Program to find the sum of odd digits using do while loop.
Developed by: Aparna RB
RegisterNumber: 212222220005
#include<stdio.h>
int main()
{    
    int sum,n,i;  
    sum=0;    
    scanf("%d",&n);   
    for(i=0;i<=n;i++)  
    {      
        if(i%2!=0)       
        {            
            sum=sum+i;    
        }    
        
    }   
    printf("%d",sum);   
    return 0;
    
}
*/
```

## Output:

<img width="1314" height="364" alt="image" src="https://github.com/user-attachments/assets/55d09e61-4d1e-4d6c-9710-cb7606b43cd2" />


## Result:
Thus the program was executed and the output was verified successfully.
