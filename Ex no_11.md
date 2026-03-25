# EX 11 C Program to convert a given decimal value to binary using function without arguments with return type.
## DATE:17/03/2026
## AIM:
To write a C Program to convert a given decimal value to binary using function without arguments with return type.

## Algorithm
Start.
Declare a integer variable
Define a function named dectobin.
Return the integer.
Read the value using scanf.
Convert decimal to binary value.
Print the dectobin
End.   

## Program:
```
/*
Program to C Program to convert a given decimal value to binary using function without arguments with return type.
#include<stdio.h>
Int dectobin(int d){
int bin =0,base=1,rem; 
while(d>0)
{
rem=d%2; 
bin=bin+rem*base; 
d=d/2; 
base=base*10;
}
printf(" = %d in binary",bin); 
return 0;
}
int main()
{
int dec; 
scanf("%d",&dec);
printf("%d in decimal",dec); 
dectobin(dec);
return 0;
Developed by: ARIGALA LAVANYA
RegisterNumber:  212222060019
*/
```

## Output:
<img width="769" height="282" alt="image" src="https://github.com/user-attachments/assets/8bcba1b3-698c-44bd-9d86-5eb24e164183" /> 



## Result:
Thus the program was executed and the output was verified successfully.
