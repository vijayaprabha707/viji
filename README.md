#include<stdio.h>
#include<conio.h>
void main()
{
int a;
printf("enter the number");
scanf("%d",&a);
if(a>0)
{
printf("the given is positive number");
}
elseif(a<0)
{
printf("the given is negative number");
}
else
{
printf("the given is zero");
}
getch();
}
