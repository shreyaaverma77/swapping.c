#include<stdio.h>
int main()
{
int num1 , num2 , temp;

printf("Enter first number:");
scanf("%d" , &num1);

printf("Enter second number:");
scanf("%d" , &num2);

temp=num1;
num1=num2;
num2=temp;

printf("After Swapping,"
"First number: %d"
"Second number: %d", num1, num2);

return 0;

}


