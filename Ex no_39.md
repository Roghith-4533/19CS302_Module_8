# EX 39 C program to find sum of digits.
## DATE:
## AIM:
To write a C program to find sum of digits.

## Algorithm
1.Start

2.Define a variables.

3.Write a program to print the English word corresponding to the given number.

4.Read the value using scanf.

5.Ask the user to make an input.

6.Print out the answer.

7.End   

## Program:
```
#include<stdio.h>
int main()
{
    int a,s,i,y=0;
    scanf("%d",&a);
    for(i=1;i<=5;i++)
    {
        s=a%10;
        y=y+s;
        a=a/10;
    }
    printf("%d",y);
}
```

## Output:

![WhatsApp Image 2025-05-21 at 09 40 07_00e8eec7](https://github.com/user-attachments/assets/c59cd74d-b1a3-4592-b31c-684ff03bde13)



## Result:
Thus the program was executed and the output was verified successfully.
