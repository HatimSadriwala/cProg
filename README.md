# cProg
/*Program for displaying Stars in day*/
#include<stdio.h>
#include<conio.h>
void main()
{
int a,c,f,i,b,j;
printf("Enter a Number:");
scanf("%d",&a);
printf("\n");
for(c=0;c<=10;c++)
{
printf("\t");
for(f=c;f<a;f++)
{
printf("\t *");
}
printf("\n");
}
j=0;
b=0;
printf("Enter a Number:");
scanf("%d",&i);
for(b=0;b<=i;b++)
{
for(j=0;j<=b;j++)
{
printf("*");
}
printf("\n");
}
getch();
}
