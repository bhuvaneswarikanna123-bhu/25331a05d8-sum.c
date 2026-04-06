# 25331a05d8-sum.c
#include<stdio.h>
int sum(int a,int b);
int main(){
int num1,num2,result;
printf("_25331a05d8_\n");
printf("enter first number:");
scanf("%d",&num1);
printf("enter second number:");
scanf("%d",&num2);
result = sum(num1,num2);
printf("sum=%d",result);
return 0;
}
int sum (int a,int b)
{
return a+b;
}


